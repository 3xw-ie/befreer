<template>
  <div
    ref="path"
    class="flow"
  >
    <!-- <svg
      :style="leftToRight ? '' : 'transform: scale(1, -1)'"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 400 100"
      stroke-width="8px"
      fill="none"
      preserveAspectRatio="xMidYMid slice"
      class="w-full h-full text-green-lighter stroke-current"
    >
      <path
        id="path"
        d="M 4 0 v 50 h 392 v 50"
      />
    </svg>
    <svg
      id="chevron"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 20"
      class="absolute w-8 text-green-dark fill-current"
      style="left: -16px; top: -11px; opacity: 0;"
    >
      <path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/>
    </svg> -->
    <!-- <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
    <svg id="chevron" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="absolute w-8 text-green-dark fill-current" style="left: -16px; top: -11px; opacity: 0;"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg> -->
    <!-- eslint-enable -->
  </div>
</template>

<script>
export default {
  props: {
    container: {
      type: Object,
      default: null
    },
    leftToRight: {
      type: Boolean,
      default: true
    },
    delay: {
      type: Number,
      default: 0
    }
  },
  data() {
    return {
      chevrons: []
    }
  },
  mounted() {
    // this.cloneChevrons(15)
    try {
      // this.animate(this.delay)
    } catch (error) {
      console.error(error)
    }
  },
  methods: {
    cloneChevrons(quantity) {
      this.chevrons.push(this.$refs.chevron)
      Array.from(Array(quantity)).forEach((x, i) => {
        const chevron = this.$refs.chevron.cloneNode(true)
        this.chevrons.push(chevron)
        this.$refs.path.appendChild(chevron)
      })
    },
    animate(delay) {
      const path = this.$refs.path
      const container = this.$parent.$refs.container
      const elements = document.querySelectorAll('#chevron')
      const height = path.clientHeight
      const width = path.clientWidth
      const xDistance = width - (width * 8 / 400 ) // eslint-disable-line
      const positions = {
        startX: this.leftToRight ? 0 : xDistance,
        startY: -5,
        midY: (height - 8) / 2,
        endX: this.leftToRight ? xDistance : xDistance * -1,
        endY: height - 8
      }
      const keyframes = [
        {
          transform: `translate(${positions.startX}px, ${positions.startY}px) rotate(0deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 1/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 2/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 3/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 4/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 5/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 6/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 7/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 8/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 9/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 10/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 11/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 12/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 13/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 14/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX * 15/16}px, ${positions.midY}px) rotate(${this.leftToRight ? '-' : ''}90deg)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX}px, ${positions.midY}px) rotate(0)`, // eslint-disable-line
          opacity: 1
        },
        {
          transform: `translate(${positions.startX + positions.endX}px, ${positions.endY}px) rotate(0)`, // eslint-disable-line
          opacity: 1
        }
      ]
      const options = {
        duration: 4000,
        iterations: Infinity
      }
      elements.forEach(element => {
        element.animate(keyframes, { delay, ...options })
        delay += 250
      })
    }
  }
}
</script>

<style>
@media screen and (max-width: 375px) {
  .flow {
    width: calc((320px - 96px - 32px) + (2 * 4px * 0.625923913));
    height: auto;
    margin-left: calc(-4px * 0.625923913);
    margin-bottom: -4px;
  }
}

@media screen and (min-width: 376px) {
  .flow {
    width: calc((376px - 96px - 32px) + (2 * 4px * 0.7931521739));
    height: 64px;
    margin-left: calc(-4px * 0.7931521739);
  }
}

@media screen and (min-width: 576px) {
  .flow {
    width: calc((576px - 128px - 32px) + (2 * 4px * 1.249673913));
    height: 80px;
    margin-left: calc(-4px * 1.249673913);
  }
}

@media screen and (min-width: 768px) {
  .flow {
    width: calc((768px - 128px - 32px) + (2 * 4px * 1.7714130435));
    height: 80px;
    margin-left: calc(-4px * 1.7714130435);
  }
}

@media screen and (min-width: 992px) {
  .flow {
    width: calc(((992px - 480px - 32px) / 2) + (2 * 4px));
    height: calc((((992px - 480px -32px) / 2) + (2 * 4px)) / 4.6);
    margin-left: calc(-4px * 0.8266666667);
  }
}

@media screen and (min-width: 1200px) {
  .flow {
    width: calc(((1200px - 480px - 32px) / 2) + (2 * 4px));
    height: calc((((1200px - 480px - 32px) / 2) + (2 * 4px)) / 4.6);
    margin-left: -4px;
  }
}
</style>
