<template>
	<v-app>
		<v-content>
			<playground></playground>
		</v-content>
	</v-app>
</template>

<script>
import Playground from './Playground'

export default {
  name: 'App',

  components: {
    Playground,
  },

  data: () => ({
    //
  }),
};
</script>
