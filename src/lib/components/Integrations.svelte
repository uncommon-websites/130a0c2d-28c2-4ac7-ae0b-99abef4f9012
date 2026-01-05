<script lang="ts">
	import { Globe, ShoppingCart, Cloud, Smartphone, TrendingUp, Database } from 'lucide-svelte';
</script>

<section class="bg-gray-950 text-white py-24 px-6 md:px-12">
	<div class="max-w-7xl mx-auto">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
			<!-- Content -->
			<div>
				<h2 class="text-5xl md:text-6xl font-bold tracking-tight mb-6">
					Als het online is, verbinden we het met Odoo
				</h2>
				<p class="text-xl text-gray-400 mb-8 leading-relaxed">
					Het gaat ons erom uw Odoo-ervaring een boost te geven door middel van naadloze integraties. Stel u voor dat u uw online winkel synchroniseert, sociale mediakanalen koppelt of IoT-apparaten aansluit voor realtime tracking.
				</p>
				<p class="text-lg text-gray-400 leading-relaxed">
					Van e-commerceplatforms tot boekhoudsoftware, marketingtools tot weer-API's – als het online is, verbinden we het met Odoo.
				</p>
			</div>

			<!-- Integration Icons Grid -->
			<div class="grid grid-cols-3 gap-6">
				<div class="border border-gray-800 bg-black/50 p-6 flex flex-col items-center justify-center aspect-square hover:border-primary-700 transition-colors">
					<ShoppingCart class="w-8 h-8 text-primary-400 mb-3" />
					<span class="text-sm text-gray-400 text-center">E-commerce</span>
				</div>
				<div class="border border-gray-800 bg-black/50 p-6 flex flex-col items-center justify-center aspect-square hover:border-primary-700 transition-colors">
					<Cloud class="w-8 h-8 text-primary-400 mb-3" />
					<span class="text-sm text-gray-400 text-center">Cloud services</span>
				</div>
				<div class="border border-gray-800 bg-black/50 p-6 flex flex-col items-center justify-center aspect-square hover:border-primary-700 transition-colors">
					<Database class="w-8 h-8 text-primary-400 mb-3" />
					<span class="text-sm text-gray-400 text-center">Boekhouding</span>
				</div>
				<div class="border border-gray-800 bg-black/50 p-6 flex flex-col items-center justify-center aspect-square hover:border-primary-700 transition-colors">
					<Smartphone class="w-8 h-8 text-primary-400 mb-3" />
					<span class="text-sm text-gray-400 text-center">IoT devices</span>
				</div>
				<div class="border border-gray-800 bg-black/50 p-6 flex flex-col items-center justify-center aspect-square hover:border-primary-700 transition-colors">
					<TrendingUp class="w-8 h-8 text-primary-400 mb-3" />
					<span class="text-sm text-gray-400 text-center">Marketing</span>
				</div>
				<div class="border border-gray-800 bg-black/50 p-6 flex flex-col items-center justify-center aspect-square hover:border-primary-700 transition-colors">
					<Globe class="w-8 h-8 text-primary-400 mb-3" />
					<span class="text-sm text-gray-400 text-center">Web API's</span>
				</div>
			</div>
		</div>
	</div>
</section>
