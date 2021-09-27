<div class="container">
	<div>test</div>
</div>
<style>
	.container:before {
    content: '';
    position: absolute;
    top: -1px;
    right: -1px;
    transform: translate(50%, -50%);
    width: 700px;
    height: 700px;
    border-radius: 50%;
    background: linear-gradient(#2baa83, #b3dc7c);
    mix-blend-mode: darken;
  }
</style>