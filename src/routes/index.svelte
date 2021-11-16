<script context="module">
  export async function load() {
    return {
      status: 302,
      redirect: '/page?param=1%2C2'
    };
  }
</script>