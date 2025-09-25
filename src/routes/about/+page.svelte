<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
		}
	];
</script>

<SecondaryHero
	title="Learning that actually sticks"
	subtitle="Smarter training, built for brains"
	imageSrc="/generated/image-photorealistic-candid-scene-of-a-diverse.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We saw L&D managers struggling with the same frustrating cycle: hours spent creating training programs, only to watch completion rates hover around 30%. Employees weren't lazy or uninterested—they were drowning in one-size-fits-all content that didn't match how they actually learn. Some people need visuals, others learn by doing, and many prefer audio explanations. Traditional corporate training ignored these differences entirely.",
		"That's when we realized the solution wasn't just better content—it was smarter delivery. We developed AI that observes how each employee engages with material and adapts in real-time. Visual learners get more diagrams and infographics. Hands-on learners get interactive simulations. Audio learners get rich narration and discussions. Suddenly, the same content becomes personally meaningful for everyone.",
		"Today, our partners see 70% higher completion rates because learning finally feels natural instead of forced. We're not just changing how companies train—we're proving that when you respect how people actually learn, they surprise you with what they can accomplish. Our vision is simple: transform the entire $366B corporate training industry by making every learning experience as personal as having your own dedicated coach."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Haroon Choudery",
			position: "Founder & CEO",
			bio: "Passionate about transforming corporate learning through personalized, brain-based training approaches.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Martinez",
			position: "VP of Learning Science",
			bio: "Former neuroscientist turned learning engineer, designing AI that adapts to individual learning styles.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Marcus Chen",
			position: "Head of Product",
			bio: "Enterprise software veteran focused on creating intuitive tools that L&D teams actually love using.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to transform your training?"
	subtitle="See personalized learning in action"
	description="Join L&D leaders seeing 70% higher completion rates with learning that adapts to each employee's preferred style."
/>
