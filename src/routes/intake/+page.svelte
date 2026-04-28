<div class="mx-auto mt-10 max-w-2xl rounded-lg border border-gray-700 bg-gray-950 p-8">
	<h1 class="mb-6 text-2xl font-bold text-cyan-400">New Client Intake</h1>
    <label class="mb-4 flex flex-col text-sm text-gray-300">
		<span class="mb-1">First Name</span>
		<input
			type="text"
			required
			placeholder="Maria"
			class="w-full rounded border border-gray-600 bg-gray-800 p-3 text-white placeholder-gray-500"
		/>
	</label>
<label class="mb-4 flex flex-col text-sm text-gray-300">
		<span class="mb-1">Last Name</span>
		<input
			type="text"
			required
			placeholder="Santos"
			class="w-full rounded border border-gray-600 bg-gray-800 p-3 text-white placeholder-gray-500"
		/>
	</label>
<label class="mb-4 flex flex-col text-sm text-gray-300">
		<span class="mb-1">Email Address</span>
		<input
			type="email"
			required
			placeholder="[email protected]"
			class="w-full rounded border border-gray-600 bg-gray-800 p-6 text-white placeholder-gray-500"
		/>
	</label>
<label class="mb-4 flex flex-col text-sm text-gray-300">
		<span class="mb-1">Engagement Start Date</span>
		<input
			type="date"
			required
			class="mb-4 w-full rounded border border-gray-600 bg-gray-800 p-3 text-white"
		/>
	</label>
<label class="mb-4 flex flex-col text-sm text-gray-300">
		<span class="mb-1">Estimated Annual Revenue ($)</span>
		<input
			type="number"
			required
			step="1000"
			min="0"
			placeholder="0"
			class="w-full rounded border border-gray-600 bg-gray-800 p-3 text-green-400"
		/>
	</label>
<label class="mb-4 flex flex-col text-sm text-gray-300">
		<span class="mb-1">Service Type</span>
		<select class="w-full rounded border border-gray-600 bg-gray-800 p-3 text-white">
			<option value="" disabled selected>Select a service...</option>
			<option value="bookkeeping">Bookkeeping</option>
			<option value="tax_prep">Tax Preparation</option>
			<option value="advisory">Advisory Services</option>
		</select>
	</label>
</div>
