<script>
	import '@vidstack/player/define/dangerously-all.js';
</script>

<vds-video-player
	src="https://media-files.vidstack.io/720p.mp4"
	poster="https://media-files.vidstack.io/poster.png"
	controls
	loading="lazy"
>
	<!-- `<source>` and `<track>` elements can go here. -->
	<vds-media-ui slot="ui">
		<!-- UI elements go here. -->
	</vds-media-ui>
</vds-video-player>
