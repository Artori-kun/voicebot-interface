<template>
	<div>
		<a href="https://rasa.com/" target="_blank">
			<img class="logo" src="@/assets/icon/Xiu_icon2.jpg">
		</a>
		<p>
      <b style="font-size: x-large">Xỉu đang ngủ nè (ﾐᵕᆽᵕﾐ)</b>
      <br>
			<br>Gọi tui dậy đi.
		</p>
		<div style="position: relative; height: 50px;" class="container-fluid">
			<img class="arrow" src="@/assets/icon/down-arrow.svg">
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.logo {
	width: 194px;
	height: 190px;
	margin: 0 auto;
	display: block;
	margin-top: 20vh;
}
p {
	padding: 10px;
	margin-top: 85px !important;
	font-size: 12pt;
	align-items: center;
	color: white;
	text-align: center;
	line-height: 1.2em;
}
.arrow {
	width: 46px;
	height: 23px;
	display: block;
	color: white;
	left: calc(50% - 23px);
	position: absolute;
	animation: jump 1.25s linear infinite;
	@keyframes jump {
		0% {
			top: 30px;
		}
		50% {
			top: 20px;
		}
		100% {
			top: 30px;
		}
	}
}
</style>
