<template>
  <section class="___section about">
    <div class="about___text___container">
      <div class="main___heading___wrapper">
        <h1 class="main___heading">Off-Edge</h1>
      </div>
      <h2 class="header___text sub___head">
        Want to stop blending in with the masses and start standing out?
      </h2>
      <br />
      <h2 class="header___text desc">
        Say hello to unique, high-converting websites. Discover why we're the premier choice for
        unleashing your brand's creativity online.<br /><br />We've got only 1 slots left this April & we're offering one year free web hosting
        for these slots.
        <span class="differ___text">Book an appointment to get in touch with us now!</span>
      </h2>
    </div>
    <div class="about___button">
      <a @click="handleClick" class="booking___btn" href="https://tinyurl.com/offedgemail"
        >Book an appointment now</a
      >
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    handleClick() {
      fbq('track', 'Booked', { value: 'yes' })
    }
  }
}
</script>
