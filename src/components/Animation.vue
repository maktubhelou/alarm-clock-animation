<template>
  <div class="main">
    <header>
      <h1>{{ msg }}</h1>
    </header>
    <main id="main">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 1000">
        <g id="background">
          <circle id="sky" class="st0" cx="502.3" cy="520.4" r="314.3"/>
          <path id="grass" class="st1" d="M502.3 834.6c87.9 0 167.3-36.1 224.4-94.3l1.3-1.3H276.7c57.2 59 137.1 95.6 225.6 95.6z"/>
          <path id="clouds" class="st2" d="M801.4 615.6c-1.3-.1-2.5-.1-3.8-.1-5.1 0-9.9 1.2-14.2 3.1-6.8-6.4-15.9-10.3-25.9-10.3-15.7 0-29.2 9.6-34.9 23.3-8-7.5-18.8-12.1-30.7-12.1-16.7 0-31.2 9.1-39 22.6-7.7-5.5-17.1-8.7-27.2-8.7-11.4 0-21.8 4-29.9 10.8v-.9c0-22.7-18.3-41-40.9-41-10.4 0-19.8 3.9-27.1 10.3-3.9-2.2-8.5-3.5-13.4-3.5-11.6 0-21.4 7.2-25.4 17.4-3.2-1.1-6.7-1.7-10.3-1.7-4.8 0-9.3 1-13.4 2.9-6.4-6-15-9.7-24.4-9.7-14.8 0-27.5 9-32.9 21.9-7.6-7.1-17.7-11.4-28.9-11.4-15.7 0-29.4 8.6-36.8 21.3-7.2-5.1-16.1-8.2-25.6-8.2-10.7 0-20.5 3.8-28.2 10.1v-.9c0-21.4-17.3-38.7-38.5-38.7-9.8 0-18.7 3.7-25.5 9.7-3.7-2.1-8-3.3-12.6-3.3-2.5 0-5.8.1-8.1.8 14.9 45.6 40.8 86.7 73.3 120.3l450.7-.2c33.3-34.6 58.9-76.8 73.6-123.8z"/>
        </g>
        <g id="clock">
          <g id="clock-legs">
            <path id="left-leg" class="st3" d="M355.3 737.3l-2.6-1.9c-5.6-4-6.9-11.8-3-17.4l35.6-50.2 22.9 16.3-35.6 50.2c-3.9 5.7-11.7 7-17.3 3z"/>
            <path id="right-leg" class="st3" d="M648.5 737.3l2.6-1.9c5.6-4 6.9-11.8 3-17.4l-35.6-50.2-22.9 16.3 35.6 50.2c3.9 5.7 11.7 7 17.3 3z"/>
          </g>
          <g id="clock-frame">
            <circle id="clock-body" cx="503.2" cy="529.2" r="188.8" fill="#f27e5f" stroke="#000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"/>
            <circle id="clock-face" cx="503.2" cy="529.2" r="151.8" fill="#fcfbed" stroke="#000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"/>
          </g>
          <g id="top-button">
            <path id="alarm-button-pin" class="st6" d="M501.6 340.1v-13.3"/>
            <circle id="alarm-button" class="st1" cx="501.6" cy="313.5" r="13.3"/>
          </g>
          <g id="clock-points">
            <circle id="12-oclock" cx="501.6" cy="397.6" r="5.3"/>
            <circle id="11-oclock" cx="435.7" cy="415.2" r="5.3"/>
            <circle id="10-oclock" cx="387.5" cy="463.3" r="5.3"/>
            <circle id="9-oclock" cx="369.7" cy="529.1" r="5.3"/>
            <circle id="8-oclock" cx="387.3" cy="595" r="5.3"/>
            <circle id="7-oclock" cx="435.4" cy="643.2" r="5.3"/>
            <circle id="6-oclock" cx="501.2" cy="660.9" r="5.3"/>
            <circle id="5-oclock" cx="567.1" cy="643.4" r="5.3"/>
            <circle id="4-oclock" cx="615.3" cy="595.2" r="5.3"/>
            <circle id="3-oclock" cx="633.1" cy="529.4" r="5.3"/>
            <circle id="2-oclock" cx="615.5" cy="463.6" r="5.3"/>
            <circle id="1-oclock" cx="567.4" cy="415.3" r="5.3"/>
          </g>
          <g id="clock-main-center">
            <ellipse id="reflection" transform="rotate(131.928 374.395 420.521)" class="st2" cx="374.4" cy="420.5" rx="19.6" ry="7.6"/>
            <circle id="center" class="st1" cx="503.2" cy="529.2" r="43"/>
            <path id="buzzer-left-pin" class="st7" d="M374.4 391l-65.6-63.4"/>
            <path id="buzzer-right-pin" class="st7" d="M632.9 392l65.6-63.4"/>
            <path id="minute-hand" class="st8" d="M449.5 427.9c-3.2 2.2-4 6.5-2.3 9.9l38.2 74.2c.9 1.7 2.7 2.8 4.7 3.3 1.9.5 3.6 1.7 4.5 3.5l5.8 11.2c.6 1.2 2.2 1.7 3.4 1.1 1.2-.6 1.7-2.2 1.1-3.4l-5.1-9.9c-1.1-2.1-1.4-4.6-.6-6.9.6-1.9.7-4-.2-5.8l-38.4-74.4c-2.1-4.1-7.3-5.5-11.1-2.8z"/>
            <path id="hour-hand" class="st8" d="M592.7 557c.7-3.8-1.8-7.5-5.4-8.6l-60.1-19.2c-1.9-.6-3.9-.1-5.6 1-1.7 1-3.8 1.4-5.7.7l-12-3.8c-1.3-.4-2.8.3-3.2 1.6-.4 1.3.3 2.8 1.6 3.2l10.6 3.4c2.3.7 4.3 2.3 5.3 4.4.9 1.8 2.3 3.3 4.3 4l60.4 19.3c4.3 1.3 8.9-1.4 9.8-6z"/>
            <circle id="center-point" class="st0" cx="503.2" cy="529.2" r="10.2"/>
          </g>

          <g id="alarm-bells">
            <path id="vibration-top-right" class="st6" d="M553.8 313.2l-22.7-22.7 28.6 1.3.1-31.8 22.5 24.6 15.4-20 4.2 24 18.1-4.2"/>
            <path id="vibration-bottom-right" class="st6" d="M712 470.8l15.6 23.1 5.9-28.6 29.3 1.4-24.8-21.1 20.8-17.3-24.4-6.4 2.9-15.6"/>
            <path id="vibration-top-left" class="st6" d="M451.2 311.6l18.1-23.3-26.6 2.5-2.7-31-19.3 24-15-19.4-4 23.3-17.7-4.2"/>
            <path id="vibration-bottom-left" class="st6" d="M288.1 470.1l-18.2 21.8-1.3-26.8-28.7.1 25.2-19.6-19.6-17.8 27.2-3.2-5.1-17.3"/>
            <path id="right-bell" class="st3" d="M689.2 338.2c-31.6-32.9-77.6-43.8-118.7-32.1l146.1 152c13.4-40.7 4.3-87-27.4-119.9z"/>
            <path id="left-bell" class="st3" d="M317.6 336.2c-31.9 32.7-41.4 78.9-28.4 119.6L436.6 305c-41-12-87-1.5-119 31.2z"/>
          </g>
        </g>
                  <g id="cloud-bubbles">
            <circle id="cloud-bubble-2" class="st2" cx="734.8" cy="583.4" r="5.5"/>
            <circle id="cloud-bubble-3" class="st2" cx="197.4" cy="579.6" r="18.8"/>
            <circle id="cloud-bubble-4" class="st2" cx="763.8" cy="622.4" r="5.5"/>
            <path id="cloud-bubble-5" class="st2" d="M791.9 597.5c3-1.5 5.4-3.7 7.1-6.4 6.9 5.4 16.5 6.7 24.9 2.6 11.8-5.7 16.7-19.9 10.9-31.7-5.7-11.8-19.9-16.7-31.7-10.9-6.3 3.1-10.6 8.6-12.4 14.8-4.4-1.7-9.4-1.7-14 .5-8.6 4.2-12.2 14.5-8 23.1 4.2 8.6 14.6 12.2 23.2 8z"/>
            <circle id="cloud-bubble-6" class="st2" cx="764" cy="544.5" r="8.7"/>
            <circle id="cloud-bubble-7" class="st2" cx="233.7" cy="593.8" r="8.3"/>
            <circle id="cloud-bubble-8" class="st2" cx="304.6" cy="608" r="6.1"/>
          </g>
      </svg>
    </main>
    <footer>
    </footer>
  </div>
</template>

<script>
import { TimelineMax } from 'greensock'

export default {
  name: 'Animation',
  data () {
    return {
      msg: 'This is where the animation magic happens!'
    }
  },
  mounted () {
    let tl = new TimelineMax()
    tl.from('#background', 2, { opacity: 0 })
    tl.from('#cloud-bubbles', 2, { opacity: 0 })
    tl.from(['.st0','st1'], 2, { fill: '#777' })

    let vibrateTl = new TimelineMax()
    vibrateTl.fromTo(['#alarm-bells', '#clock-legs', '#clock'], 0.05, { y: -2, x: -4, ease: Elastic.easeInOut.config(1, 0.3) }, { y: 2, x: 4, ease: Elastic.easeOut.config(1, 0.3) }).repeat(250)

    let minuteHandTimeLine = new TimelineMax()
    minuteHandTimeLine.to('#minute-hand', 6, {
      rotation: 360, 
      transformOrigin: "100% 100%",
      ease: Power0.easeNone
    }, 0)

    let hourHandTimeLine = new TimelineMax()
    hourHandTimeLine.to('#hour-hand', 72, {
      rotation: 360,
      transformOrigin: "0% 0%",
      ease: Power0.easeNone
    }, 0)
    minuteHandTimeLine.repeat(-1)
    hourHandTimeLine.repeat(-1)

  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.st0,
.st1,
.st2,
.st3,
.st6,
.st7,
.st8 {
  fill: #f2b770;
  stroke: #000;
  stroke-width: 2;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
}
.st1,
.st2,
.st3,
.st6,
.st7,
.st8 {
  fill: #679e4a;
}
.st2,
.st3,
.st6,
.st7,
.st8 {
  fill: #fff;
}
.st3,
.st6,
.st7,
.st8 {
  fill: #6e93e5;
}
.st6,
.st7,
.st8 {
  fill: none;
}
.st7,
.st8 {
  stroke-width: 3;
}
.st8 {
  fill: #d1cfbd;
  stroke-width: 2;
}
</style>
