<template>
	<div class="presentation">
		<p>
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo provident
			voluptatibus saepe, adipisci atque ad dignissimos, minima, aliquam ut
			maiores laborum nam molestias culpa sapiente velit impedit numquam. Atque
			illum dolorem aperiam ducimus nostrum magnam aliquam explicabo suscipit
			vel ipsa perferendis, maiores ex! Distinctio, sit beatae commodi voluptate
			veritatis, illo eos aperiam earum exercitationem repellat sunt, cum eaque
			vero excepturi!
		</p>

		<img src="@/assets/img/presentation.svg" alt="Apresentação iBook" />
	</div>
</template>

<style lang="scss" scoped>
.presentation {
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	grid-gap: 2rem;
	align-items: center;
	@include screen('small', 'medium') {
		grid-template-columns: 1fr;
	}
	p {
		line-height: 26px;
	}
	img {
		max-width: 100%;
	}
}
</style>
