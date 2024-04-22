<script>
	import '../app.postcss';
	import SvelteSeo from 'svelte-seo';
</script>

<SvelteSeo
	title="Hosting On-Premises"
	description="Find the most Hosting On-Premises open-source, Hosting On-Premises projects on the web."
	openGraph={{
		title: 'HHF Tech Tips Hosting On-Premises',
		description:
			'Find the most Hosting On-Premises open-source, Hosting On-Premises projects on the web. HHF TechTips.',
		image: 'https://hosting-on-premises.hhf.co.in/hosting-on-premises_og.png',
		url: 'https://hosting-on-premises.hhf.co.in',
		type: 'website',
		images: [
			{
				url: 'https://hosting-on-premises.hhf.co.in/hosting-on-premises_og.png',
				width: 1200,
				height: 630,
				alt: 'HHF Hosting On-Premises'
			}
		],
		site_name: 'HHF Tech Tips Hosting On-Premises'
	}}
	twitter={{
		card: 'summary_large_image',
		title: 'HHF Tech Tips Hosting On-Premises',
		description:
			'Find the most Hosting On-Premises open-source, Hosting On-Premises projects on the web. HHF TechTips.',
		image: 'https://hosting-on-premises.hhf.co.in/hosting-on-premises_og.png'
	}}
/>
<slot />
