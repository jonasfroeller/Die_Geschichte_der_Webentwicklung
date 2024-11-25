<script setup lang="ts">
import ChromeIcon from '~icons/logos/chrome';
import SafariIcon from '~icons/logos/safari';
import EdgeIcon from '~icons/logos/microsoft-edge';
import FirefoxIcon from '~icons/logos/firefox';
import OperaIcon from '~icons/logos/opera';

const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}

// icons are not auto-imported, because they are rendered before that...
/* const icons = [
  'logos-chrome',
  'logos-safari',
  'logos-microsoft-edge',
  'logos-firefox',
  'logos-opera'
] */

const icons = [
  ChromeIcon,
  SafariIcon,
  EdgeIcon,
  FirefoxIcon
]
</script>

<template>
    <div>
        <div class="flex pb-4">
            <div 
                v-for="(icon, index) in icons" 
                :key="index"
                v-motion
                :initial="{ opacity: 75, y: 20, scale: 0.8 }"
                :enter="final"
                class="relative -ml-2 first:ml-0"
            >
                <component :is="icon" class="w-8 h-8" />
            </div>

            <img
                v-motion
                :initial="{ opacity: 75, y: 20, scale: 0.8 }"
                :enter="final"
                class="relative -ml-2 first:ml-0 w-8 h-8"
                border="rounded"
                src="/image.png"
            > <!-- https://commons.wikimedia.org/wiki/File:Samsung_Internet_logo.svg -->

            <div
                v-motion
                :initial="{ opacity: 75, y: 20, scale: 0.8 }"
                :enter="final"
                class="relative -ml-2 first:ml-0"
            >
                <logos-opera :is="icon" class="w-8 h-8" />
            </div>
        </div>
    </div>
</template>
