<template>
	<div class="home">
		<div class="sub-wrap">
			<div class="sub-wrap-1">
				<a class="starbucks-icon" href="/starbucks.co.kr">
					<img :src="require('@/assets/images/starbucks_icon.png')">
				</a>
				<nav class="nav1">
					<ul>
						<li class="nav1-li-1">Sign In</li>
						<li class="nav1-li-2">My Starbucks</li>
						<li class="nav1-li-3">Customer Service & Ideas</li>
						<li class="nav1-li-4">Find a Store</li>
					</ul>
					<button class="search-btn">
						<img :src="require('@/assets/images/outline_search.png')">
					</button>
				</nav>
				<nav class="nav2">
					<ul>
						<li class="nav2-li-1">COFFEE</li>
						<li class="nav2-li-2">MENU</li>
						<li class="nav2-li-3">STORE</li>
						<li class="nav2-li-4">RESPONSIBILITY</li>
						<li class="nav2-li-5">STARBUCKS REWARDS</li>
						<li class="nav2-li-6">WHAT'S NEW</li>
					</ul>
				</nav>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "Home",
};
</script>
