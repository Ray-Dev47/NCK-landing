<template>
	<div class="border-t-2 flex justify-between">
		<div class="w-2/5">
			<!-- card info -->
			<div class="text-left">
				<div class="font-bold  mt-6 text-xl">
					Payment Information
				</div>
				<div class="py-4 mb-8 text-gray-400">
					Choose your method of payment
				</div>
				<div class="border-2 border-red-500 py-36 px-64">
					card contents
				</div>
			</div>
		</div>

		<!-- card end -->

		<!-- input info -->
		<div class="w-6/12">
			<div class="mt-6 text-left  mb-11 flex flex-row justify-end">
				<!-- logo start -->
				<div>
					<a href="#">
						<img class=" mx-2 h-16 " src="@/assets/img/visa.jpg" alt="visa" />
					</a>
				</div>
				<div>
					<a href="#">
						<img
							class=" mx-2 h-16 w-26 ml-7 "
							src="@/assets/img/discover.png"
							alt="visa"
						/>
					</a>
				</div>
				<div>
					<a href="#">
						<img
							class=" mx-2 h-16 w-26 ml-7 "
							src="@/assets/img/paypal.png"
							alt="visa"
						/>
					</a>
				</div>
			</div>
			<!-- logo end -->

			<div class="">
				<!-- input -->
				<div class="flex flex-row">
					<form action="#">
						<div class="flex flex-row">
							<div>
								<label
									class="block text-gray-700 text-left mb-2 text- font-normal"
									for="username"
									>Credit card number</label
								>
								<div class="w-80 h-auto">
									<input
										type="text"
										class="form-input font-normal text-left  bg-gray-100  border-gray-300 py-3 h-full pl-6 border-t-2 text- w-full border-r-2 rounded border-l-2 border-b-2 placeholder-gray-900 mb-5"
										placeholder="4324  5433  9382  1030"
									/>
								</div>
							</div>

							<div class="ml-6">
								<label
									class="block text-gray-700 text-left mb-2 text- font-normal"
									for="username"
									>Expiration date</label
								>
								<div class="w-80 h-auto ">
									<input
										type="text"
										class="form-input font-normal text-left  bg-gray-100  border-gray-300 py-3 h-full pl-6 border-t-2 text- w-full border-r-2 rounded border-l-2 border-b-2 placeholder-gray-900 mb-5"
										placeholder="03/24"
									/>
								</div>
							</div>
						</div>

						<div class="flex flex-row my-4">
							<div>
								<label
									class="block text-gray-700 text-left mb-2 text- font-normal"
									for="username"
									>Security code</label
								>
								<div class="w-80 h-auto">
									<input
										type="text"
										class="form-input font-normal text-left  bg-gray-100  border-gray-300 py-3 h-full pl-6 border-t-2 text- w-full border-r-2 rounded border-l-2 border-b-2 placeholder-gray-900 mb-5"
										placeholder="420"
									/>
								</div>
							</div>

							<div class="ml-6">
								<label
									class="block text-gray-700 text-left mb-2 text- font-normal"
									for="username"
									>Postal Code</label
								>
								<div class="w-80 h-auto ">
									<input
										type="text"
										class="form-input font-normal text-left  bg-gray-100  border-gray-300 py-3 h-full pl-6 border-t-2 text- w-full border-r-2 rounded border-l-2 border-b-2 placeholder-gray-900 mb-5"
										placeholder="10119"
									/>
								</div>
							</div>
						</div>
						<div class="text-left">
							<input
								type="radio"
								class="form-radio"
								name="a"
								value="personal"
							/>
							<span class="ml-2">Use this card for next time purchases</span>
						</div>
						<div class="py-4">
							<button
								class="bg-blue-700 hover:bg-blue-500 text-lg text-white font-semibold py-4 w-full rounded focus:outline-none focus:shadow-outline"
								type="button"
							>
								Add card
							</button>
						</div>
					</form>
				</div>
			</div>
		</div>
	</div>
</template>
