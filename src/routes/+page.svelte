<script lang="ts">
  import type { ActionData } from './$types';

  export let form: ActionData;
</script>

<h1>Click inside the input element and hit enter</h1>
<form method="post" action="/">
  <input type="text" name="test">
</form>
