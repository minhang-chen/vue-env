<template>
	<set-title title="tpl-form">
		<tpl-content />
	</set-title>
</template>

<script>
import Content from '@components/__tpl__/form/content';

export default {
	name: 'tpl-form',
	components: {
		'tpl-content': Content
	},
	data() {
		return {
		};
	},
	created() {
	},
	methods: {
	},
};
</script>

<style lang="scss" scoped>
</style>
