<script lang="ts">
	import { Workflow, Zap, Code, Palette } from 'lucide-svelte';
</script>

<section class="bg-black text-white py-24 px-6 md:px-12">
	<div class="max-w-7xl mx-auto">
		<div class="mb-16">
			<h2 class="text-5xl md:text-6xl font-bold tracking-tight mb-6">
				Digitaliseer uw processen met Odoo
			</h2>
			<p class="text-xl text-gray-400 max-w-3xl">
				Als officiële Odoo-partners helpen wij uw bedrijf bloeien in het digitale tijdperk. Van startups tot volwassen ondernemingen, ons team van experts werkt nauw met u samen om processen te stroomlijnen en automatiseren.
			</p>
		</div>

		<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
			<!-- Processen stroomlijnen -->
			<div class="border border-gray-800 bg-gray-950/50 p-8 hover:border-primary-700 transition-colors">
				<div class="w-12 h-12 bg-primary-600/10 rounded-lg flex items-center justify-center mb-6">
					<Workflow class="w-6 h-6 text-primary-400" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">Processen stroomlijnen</h3>
				<p class="text-gray-400 leading-relaxed">
					We analyseren en verbeteren uw bedrijfsprocessen voordat we Odoo implementeren. Door uw workflows te stroomlijnen, bereiden we u voor op een succesvolle digitale transformatie.
				</p>
			</div>

			<!-- Automatiseren -->
			<div class="border border-gray-800 bg-gray-950/50 p-8 hover:border-primary-700 transition-colors">
				<div class="w-12 h-12 bg-primary-600/10 rounded-lg flex items-center justify-center mb-6">
					<Zap class="w-6 h-6 text-primary-400" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">Automatiseren</h3>
				<p class="text-gray-400 leading-relaxed">
					Wij helpen bedrijven hun activiteiten effectief te digitaliseren en automatiseren. Van gestroomlijnde configuraties voor startups tot complexe oplossingen voor internationale bedrijven.
				</p>
			</div>

			<!-- API's en integratie -->
			<div class="border border-gray-800 bg-gray-950/50 p-8 hover:border-primary-700 transition-colors">
				<div class="w-12 h-12 bg-primary-600/10 rounded-lg flex items-center justify-center mb-6">
					<Code class="w-6 h-6 text-primary-400" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">API's en integratie</h3>
				<p class="text-gray-400 leading-relaxed">
					Onze expertise zorgt ervoor dat Odoo naadloos aansluit op uw bestaande software, waardoor een soepele gegevensstroom en samenhangende activiteiten ontstaan.
				</p>
			</div>

			<!-- Custom UI development -->
			<div class="border border-gray-800 bg-gray-950/50 p-8 hover:border-primary-700 transition-colors">
				<div class="w-12 h-12 bg-primary-600/10 rounded-lg flex items-center justify-center mb-6">
					<Palette class="w-6 h-6 text-primary-400" />
				</div>
				<h3 class="text-2xl font-semibold mb-4">Custom UI development</h3>
				<p class="text-gray-400 leading-relaxed">
					We maken op maat gemaakte interfaces die perfect aansluiten bij uw merk en workflow, waardoor een naadloze gebruikerservaring wordt gegarandeerd met de krachtige backend van Odoo.
				</p>
			</div>
		</div>
	</div>
</section>
