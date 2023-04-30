<script>
  import { Node, Svelvet, Minimap, Controls } from 'svelvet';
</script>

<div id="fixed" class="h-screen">
<Svelvet theme="dark" snapTo={22} id="my-canvas" TD controls>
  <Node />
  <Node id="alpha" bgColor="blueviolet" label="Default Node" center />
</Svelvet>
</div>