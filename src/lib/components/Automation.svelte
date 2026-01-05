<script lang="ts">
	import { CheckCircle } from 'lucide-svelte';
</script>

<section class="bg-black text-white py-24 px-6 md:px-12">
	<div class="max-w-7xl mx-auto">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
			<!-- Image/Visual Side -->
			<div class="order-2 lg:order-1">
				<div class="border border-gray-800 bg-gradient-to-br from-primary-950/20 to-gray-950 p-12 aspect-square flex items-center justify-center">
					<div class="text-center">
						<div class="w-24 h-24 bg-primary-600/20 rounded-full flex items-center justify-center mx-auto mb-6">
							<CheckCircle class="w-12 h-12 text-primary-400" />
						</div>
						<p class="text-2xl font-semibold text-gray-300">Automatisering voor<br>elk bedrijf</p>
					</div>
				</div>
			</div>

			<!-- Content -->
			<div class="order-1 lg:order-2">
				<h2 class="text-5xl md:text-6xl font-bold tracking-tight mb-6">
					Uw processen, geautomatiseerd
				</h2>
				<p class="text-xl text-gray-400 mb-8 leading-relaxed">
					Stel je voor dat jouw team bevrijd is van repetitieve taken en zich richt op groei en innovatie. Stop met het handmatig invoeren van gegevens en het verspillen van tijd.
				</p>
				<p class="text-lg text-gray-400 mb-8 leading-relaxed">
					Door Odoo als uw digitale commandocentrum te gebruiken, kunnen we vrijwel elk proces automatiseren. Van lead nurturing tot voorraadbeheer, van marketing tot klantenservice, van HR tot boekhouding.
				</p>
				
				<div class="space-y-4">
					<div class="flex items-start gap-3">
						<CheckCircle class="w-5 h-5 text-primary-400 mt-1 flex-shrink-0" />
						<p class="text-gray-300">Automatisering toegankelijk voor bedrijven van elke omvang</p>
					</div>
					<div class="flex items-start gap-3">
						<CheckCircle class="w-5 h-5 text-primary-400 mt-1 flex-shrink-0" />
						<p class="text-gray-300">Gebouwd bovenop het krachtige Odoo-platform</p>
					</div>
					<div class="flex items-start gap-3">
						<CheckCircle class="w-5 h-5 text-primary-400 mt-1 flex-shrink-0" />
						<p class="text-gray-300">Focus op succes en toekomstige groei</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
