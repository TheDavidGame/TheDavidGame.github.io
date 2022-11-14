<template>
  <div>
    <head>
      <title>developer portfolio</title>
      <link
        rel="apple-touch-icon"
        sizes="180x180"
        href="../static/apple-touch-icon.png"
      />
      <link
        rel="icon"
        type="image/png"
        sizes="32x32"
        href="../static/favicon-32x32.png"
      />
      <link
        rel="icon"
        type="image/png"
        sizes="16x16"
        href="../static/favicon-16x16.png"
      />
      <link rel="manifest" href="../static/site.webmanifest" />
      <link
        rel="mask-icon"
        href="../static/safari-pinned-tab.svg"
        color="#5bbad5"
      />
      <link rel="shortcut icon" href="../static/favicon.ico" />
      <meta name="msapplication-TileColor" content="#2b5797" />
      <meta name="msapplication-config" content="../static/browserconfig.xml" />
      <meta name="theme-color" content="#ffffff" />
    </head>
    <div class="body">
      <div class="wrapper">
        <headerMain />
        <underHeader />
        <mainWrapper />
        <underMain />
        <videosWrapper />
        <descriptionWrapper />
      </div>
      <footerWrapper />
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {}
  },
}
</script>

<style scoped>
.body {
  background-color: #f8f7f7;
  font-family: 'Roboto';
}
.wrapper {
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 30px;
}
</style>
