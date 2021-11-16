<script context="module">
  export async function load({ page: { query } }) {
    return {
      props: { param: query.get('param') }
    };
  }
</script>

<script>
  export let param;
</script>

{param}