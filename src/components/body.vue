<template>
	<div class="border-t-2 sm:flex-col flex justify-between">
		<div class="w-2/5 sm:w-3/6">
			<!-- card info -->
			<div class="text-left">
				<div class="font-bold  mt-6 text-xl">
					Payment Information
				</div>
				<div class="py-4 mb-8 text-gray-400">
					Choose your method of payment
				</div>
				<div
					class="border-2 rounded-md bg-gradient-to-bl from-purple-500 via-pink-500 to-red-500"
				>
					<div class="pl-10 py-7 text-left font-bold text-white">
						<div class="my-3">
							CARD NUMBER
						</div>
						<div class="my-3">
							4324 5433 9382 1030
						</div>
						<div class="flex items-center">
							<div class="pl-0">
								<i class="fas fa-wifi fa-rotate-90"></i>								
							</div>
							<div>
								<img
									class=" mx-2 h-20 w-20 "
									src="@/assets/img/chip.png"
									alt="profile image"
								/>
							</div>
						</div>

						<div class="my-3">
							EXPIRATION DATE
						</div>
						<div>
							03/24
						</div>
						<div class="flex justify-between items-center">
							<div>
								John Doe
							</div>
							<div>
								<img
									class=" mr-9  h-20 w-38 "
									src="@/assets/img/mastercard.png"
									alt="profile image"
								/>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- card end -->

		<!-- input info -->
		<div class="w-6/12">
			<div class="mt-8 text-left  mb-16 flex flex-row justify-end">
				<!-- logo start -->
				<div>
					<a href="#">
						<img class=" mx-2 w-14 h-10 " src="@/assets/img/visa2.jpg" alt="visa" />
					</a>
				</div>
				<div>
					<a href="#">
						<img
							class=" mx-2 w-14 h-10 ml-7 "
							src="@/assets/img/discover2.jpg"
							alt="visa"
						/>
					</a>
				</div>
				<div>
					<a href="#">
						<img
							class="w-16 h-10 mx-14 "
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
									class="block text-gray-700 text-left mb-2 text- font-medium"
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
									class="block text-gray-700 text-left mb-2 text- font-medium"
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
									class="block text-gray-700 text-left mb-2 text- font-medium"
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
									class="block text-gray-700 text-left mb-2 text- font-medium"
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
								class="bg-blue-600 hover:bg-blue-500 text-lg text-white font-semibold py-5 w-full rounded focus:outline-none focus:shadow-outline"
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
	<!-- sumtotal section -->
	<div class="border-t-2 my-8 pr-7 ">
		<div class="flex justify-between  mt-6 text-xl font-bold">
			<div>
				Subtotal
			</div>
			<div class="mx-6 text-black font-black">
				₦2,497.00
			</div>
		</div>
		<div class="flex justify-between py-6 text-xl font-bold">
			<div>
				Estimated TAX
			</div>
			<div class="mx-6 text-black font-black">
				₦119.64
			</div>
		</div>
		<div class="flex justify-between text-xl font-bold">
			<div>Promotional Code: <span class="text-gray-400">Z4KXLM9A</span></div>
			<div class="mx-6 text-black font-black">
				₦-60.00
			</div>
		</div>
	</div>
</template>
