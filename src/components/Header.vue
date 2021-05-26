<template>
	<div
		class="font-bold text-xl flex sm:flex-col sm:py-7 sm:text-center justify-end items-center mt-5 mb-14 space-x-12"
	>
		<a href="">TRIPS</a>
		<a href="">RECENTLY VIEWED</a>
		<a href="">BOOKINGS</a>
		<!-- profile image -->
		<div>
			<a href="">
				<img
					class="rounded-full mx-2 h-20 w-20 ml-7 object-cover"
					src="@/assets/img/cardi.jpg"
					alt="profile image"
				/>
			</a>
		</div>
	</div>

	
</template>

<script>
export default {
	name: 'pink-navbar',
	data() {
		return {
			showMenu: false,
		};
	},
	methods: {
		toggleNavbar: function() {
			this.showMenu = !this.showMenu;
		},
	},
};
</script>
