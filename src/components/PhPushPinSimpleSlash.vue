/* GENERATED FILE */
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 256 256"
    :width="size"
    :height="size"
    :fill="color"
    :transform="mirrored ? 'scale(-1, 1)' : undefined"
    v-bind="$attrs"
  >
    <slot />
    <g v-if="weight === 'bold'">
      <line
        x1="128"
        y1="176"
        x2="128"
        y2="240"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="48"
        y1="40"
        x2="208"
        y2="216"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="171.6"
        y1="176"
        x2="40"
        y2="176"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="56"
        y1="176"
        x2="74.8"
        y2="69.5"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="102.1"
        y1="40"
        x2="192"
        y2="40"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
      <line
        x1="176"
        y1="40"
        x2="193.8"
        y2="140.9"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="24"
      />
    </g>
    <g v-else-if="weight === 'duotone'">
      <polygon points="56 176 80 40 176 40 200 176 56 176" opacity="0.2" />
      <line
        x1="91.2"
        y1="40"
        x2="192"
        y2="40"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="128"
        y1="176"
        x2="128"
        y2="240"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="48"
        y1="40"
        x2="208"
        y2="216"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="176"
        y1="40"
        x2="196.4"
        y2="155.7"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="171.6"
        y1="176"
        x2="40"
        y2="176"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="56"
        y1="176"
        x2="74.8"
        y2="69.5"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
    <g v-else-if="weight === 'fill'">
      <path
        d="M213.4,221.9A8.2,8.2,0,0,1,208,224a8,8,0,0,1-5.9-2.6l-34-37.4H136v56a8,8,0,0,1-16,0V184H40a8,8,0,0,1,0-16h9.3L66.2,72,42.1,45.4A8,8,0,0,1,53.9,34.6l75.2,82.8,48.5,53.2h0l36.3,40A7.9,7.9,0,0,1,213.4,221.9Zm-22.9-60.8a7.9,7.9,0,0,0,5.9,2.6,8.5,8.5,0,0,0,3.5-.8,8.1,8.1,0,0,0,4.4-8.6L185.5,48H192a8,8,0,0,0,0-16H91.2A8,8,0,0,0,86,34a9.4,9.4,0,0,0-1,1,8.3,8.3,0,0,0-1.7,4.5,1.1,1.1,0,0,0,0,.8,7.9,7.9,0,0,0,2,5.1Z"
      />
    </g>
    <g v-else-if="weight === 'light'">
      <line
        x1="91.2"
        y1="40"
        x2="192"
        y2="40"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="128"
        y1="176"
        x2="128"
        y2="240"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="48"
        y1="40"
        x2="208"
        y2="216"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="176"
        y1="40"
        x2="196.4"
        y2="155.7"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="171.6"
        y1="176"
        x2="40"
        y2="176"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
      <line
        x1="56"
        y1="176"
        x2="74.8"
        y2="69.5"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="12"
      />
    </g>
    <g v-else-if="weight === 'thin'">
      <line
        x1="91.2"
        y1="40"
        x2="192"
        y2="40"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="128"
        y1="176"
        x2="128"
        y2="240"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="48"
        y1="40"
        x2="208"
        y2="216"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="176"
        y1="40"
        x2="196.4"
        y2="155.7"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="171.6"
        y1="176"
        x2="40"
        y2="176"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
      <line
        x1="56"
        y1="176"
        x2="74.8"
        y2="69.5"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="8"
      />
    </g>
    <g v-else-if="weight === 'regular'">
      <line
        x1="91.2"
        y1="40"
        x2="192"
        y2="40"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="128"
        y1="176"
        x2="128"
        y2="240"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="48"
        y1="40"
        x2="208"
        y2="216"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="176"
        y1="40"
        x2="196.4"
        y2="155.7"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="171.6"
        y1="176"
        x2="40"
        y2="176"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
      <line
        x1="56"
        y1="176"
        x2="74.8"
        y2="69.5"
        fill="none"
        :stroke="color"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="16"
      />
    </g>
  </svg>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { SetupIconProps, PropValidator, PhosphorIcon } from "@/lib/types";
import useDefaultPropsFromContext from "@/lib/useDefaultPropsFromContext";

const component: PhosphorIcon = defineComponent({
  props: PropValidator,
  setup(props: SetupIconProps) {
    return { ...useDefaultPropsFromContext(props) };
  },
});
export default component;
</script>
