<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	title="Transform workplace learning into personalized brain training"
	subtitle="AI-powered content adaptation that matches individual learning preferences, delivering 70% higher completion rates for L&D teams at fast-growing companies."
	centered={true}
	customers={[
		{
			name: "Sarah Mitchell",
			position: "Learning & Development Manager",
			imageSrc: "/generated/image-a-professional-woman-learning-manager-in.webp"
		},
		{
			name: "Marcus Johnson", 
			position: "Training Director",
			imageSrc: "/generated/image-a-professional-male-training-director-in.webp"
		},
		{
			name: "Lisa Chen",
			position: "Corporate Learning Specialist", 
			imageSrc: "/generated/image-a-professional-woman-employee-in-her-lat.webp"
		},
		{
			name: "Ahmed Hassan",
			position: "HR Learning Leader",
			imageSrc: "/generated/image-a-professional-male-hr-leader-in-his-mid.webp"
		},
		{
			name: "Jasmine Williams",
			position: "Development Specialist",
			imageSrc: "/generated/image-a-professional-woman-development-special.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders" 
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/spotify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/atlassian.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Elena Rodriguez",
			position: "Learning & Development Director",
			company: "TechFlow Dynamics",
			quote:
				"We went from 23% to 84% course completion rates in just 3 months. The AI adaptation to individual learning styles eliminated our biggest training bottleneck and saved us over $180,000 in reduced training time.",
			image: "/generated/image-photorealistic-editorial-portrait-of-a-p.webp"
		},
		{
			name: "David Kim",
			position: "VP of People Operations",
			company: "Growth Ventures",
			quote:
				"Instead of spending 6 weeks onboarding new hires, we now complete comprehensive training in 2 weeks with 95% knowledge retention. The personalized learning paths reduced our time-to-productivity by 67%.",
			image: "/generated/image-professional-asian-male-training-directo.webp"
		},
		{
			name: "Asha Patel",
			position: "Chief Learning Officer",
			company: "InnovateCorp",
			quote:
				"The risk of compliance failures dropped to zero after implementing their brain training approach. Our audit preparation time went from 3 months to 3 weeks, and employee confidence in regulatory knowledge increased by 89%.",
			image: "/generated/image-candid-scene-of-a-professional-female-le.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to turn training into results?"
	subtitle="This isn't another LMS. It's learning that works."
	description="See how other fast-growing teams are reaching 70% higher course completion with zero content overhaul. Our platform integrates with your current tools and improves outcomes in weeks—not months."
	imageSrc="/generated/image-happy-successful-female-learning-manager.webp"
	callsToAction={[
		{
			href: "/demo",
			label: "Get a demo today",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to sales",
			variant: "secondary"
		}
	]}
/>
