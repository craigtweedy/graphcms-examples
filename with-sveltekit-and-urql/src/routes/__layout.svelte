<script>
  import { initClient } from '@urql/svelte';

  initClient({
    url: 'https://api-eu-central-1.graphcms.com/v2/ck8sn5tnf01gc01z89dbc7s0o/master',
  });
</script>

<slot />
