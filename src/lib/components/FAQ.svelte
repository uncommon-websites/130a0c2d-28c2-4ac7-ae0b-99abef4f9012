<script lang="ts">
    let openIndex: number | null = 0;

    const faqs = [
        { q: "Wat is Odoo en waarom is het geschikt voor productiebedrijven?", a: "Odoo is een open-source ERP-platform dat alle bedrijfsprocessen integreert: van productie en voorraad tot verkoop, inkoop en boekhouding. Voor productiebedrijven biedt Odoo flexibiliteit om complexe workflows en maatwerk te ondersteunen zonder de beperkingen van rigide standaardsoftware." },
        { q: "Hoe lang duurt een typische Odoo-implementatie?", a: "De duur varieert afhankelijk van de complexiteit van uw processen en het aantal modules. Een basisimplementatie voor een KMO kan 2-3 maanden duren, terwijl uitgebreidere projecten met custom modules en integraties 4-6 maanden kunnen vergen. We werken in fasen zodat u snel waarde ziet." },
        { q: "Wat kost een Odoo-implementatie?", a: "Kosten hangen af van projectomvang, aantal gebruikers, benodigde modules en customization. We werken projectgebaseerd voor implementatie en customization, aangevuld met optionele support- en onderhoudscontracten. Neem contact op voor een offerte op maat." },
        { q: "Kunnen jullie Odoo integreren met onze bestaande systemen?", a: "Ja, we hebben uitgebreide ervaring met API-integraties en koppelingen naar e-commerce platforms, boekhoudsoftware, marketing tools, IoT-apparaten en andere online systemen. We zorgen voor naadloze datastromen tussen al uw tools." },
        { q: "Wat onderscheidt Digifiers van andere Odoo-partners?", a: "We zijn gespecialiseerd in Vlaamse KMO's met complexe, maatwerk productieprocessen. Als lokale, Nederlandstalige partner kennen we de uitdagingen van customized-goods manufacturers. We passen Odoo aan uw workflow aan, niet andersom." },
        { q: "Bieden jullie support na de implementatie?", a: "Absoluut. We bieden post-go-live support en doorlopende onderhoudscontracten. Of het nu gaat om technische vragen, aanpassingen of uitbreidingen – we blijven uw partner voor de lange termijn." },
        { q: "Wat is jullie ervaring met Odoo?", a: "Ons team heeft 15+ jaar gecombineerde ERP-ervaring, waarvan 3+ jaar specifiek met Odoo. We zijn officiële Odoo Ready Partner en werken aan Silver Partner status. We hebben ervaring met zowel standaard als complexe implementaties." },
        { q: "Kunnen we Odoo uitbreiden naarmate ons bedrijf groeit?", a: "Ja, schaalbaarheid is een kernvoordeel van Odoo. U kunt beginnen met essentiële modules en later uitbreiden met extra functionaliteit, gebruikers en integraties. We bouwen implementaties die meegroeien met uw bedrijf." },
        { q: "Hoe zit het met training voor onze medewerkers?", a: "Training is een integraal onderdeel van onze implementaties. We zorgen ervoor dat uw team het systeem begrijpt en effectief kan gebruiken, met hands-on begeleiding en documentatie in het Nederlands." },
        { q: "Werken jullie ook met bedrijven buiten Vlaanderen?", a: "Onze focus ligt op Vlaamse KMO's, maar we kunnen ook projecten in de rest van België ondersteunen. Neem contact op om uw specifieke situatie te bespreken." },
    ];

    function toggle(index: number) {
        openIndex = openIndex === index ? null : index;
    }
</script>

<section class="bg-[#0a0a0a] text-white px-6 md:px-12 py-24">
    <div class="max-w-7xl mx-auto">
        <h2 class="text-3xl font-medium mb-12">Frequently Asked Questions</h2>
        
        <div class="border-t border-white/20">
            {#each faqs as faq, i}
                <div class="border-b border-white/20">
                    <button 
                        class="w-full py-6 flex justify-between items-center text-left hover:text-gray-300 transition-colors"
                        onclick={() => toggle(i)}
                        aria-expanded={openIndex === i}
                    >
                        <span class="text-lg font-light pr-8">{faq.q}</span>
                        <span class="text-xl font-light">{openIndex === i ? '×' : '+'}</span>
                    </button>
                    {#if openIndex === i}
                        <div class="pb-6 text-gray-400 font-light leading-relaxed max-w-4xl">
                            {faq.a}
                        </div>
                    {/if}
                </div>
            {/each}
        </div>
    </div>
</section>