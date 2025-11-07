<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconNetwork from "~icons/lucide/network";
	import IconDatabase from "~icons/lucide/database";
	import IconRefreshCw from "~icons/lucide/refresh-cw";
	import IconBrain from "~icons/lucide/brain";
	import IconZap from "~icons/lucide/zap";
	import IconShieldCheck from "~icons/lucide/shield-check";
</script>

<Hero
	title="Unified company context for AI workflows"
	subtitle="Real-time knowledge graph synchronization that eliminates fragmented data silos and powers accurate AI operations."
	imageSrc="/generated/image-a-small-revops-team-of-two-to-three-prof.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by forward-thinking teams"
	logoUrls={[
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/zapier.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Qontext transforms your fragmented data across CRM, documents, and communications into a unified knowledge graph that powers every AI workflow. RevOps teams at digital scale-ups use our real-time synchronization to eliminate manual prompt updates and scale AI operations from ten workflows to hundreds without engineering overhead."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "CTO",
			company: "Stealth AI Startup",
			quote:
				"Qontext reduced our engineering overhead dramatically. We went from zero to one in days, not months. The unified context layer eliminated weeks of integration work and let our team focus on building product instead of maintaining data pipelines.",
			image: "/generated/image-a-professional-asian-male-cto-age-30-45-.webp"
		},
		{
			name: "Aisha Williams",
			position: "Head of Revenue Operations",
			company: "Tacto",
			quote:
				"Our go-to-market workflows are finally on autopilot. Thanks to Qontext, prompts stay automatically up to date across all our AI processes. We've saved 15+ hours per week that used to go into manual prompt engineering and data syncing.",
			image: "/generated/image-a-confident-black-female-operations-lead.webp"
		},
		{
			name: "Henrik Lindström",
			position: "Senior AI Engineer",
			company: "Flink",
			quote:
				"Maintaining context across ten workflows was manageable, but not scalable. As AI expanded across our organization, Qontext provided a single, up-to-date hub that powers them all. It's the difference between chaos and orchestrated efficiency.",
			image: "/generated/image-a-professional-caucasian-male-senior-eng.webp"
		}
	]}
/>

<Features
	title="Platform capabilities"
	subtitle="Unified context infrastructure that eliminates data silos and powers accurate AI workflows at scale"
	features={[
		{
			title: "Knowledge graph synchronization",
			description:
				"Automatically structure and link data from CRM, documents, conversations, and email to reveal relationships your AI needs. Real-time synchronization ensures your context stays fresh without manual updates.",
			icon: IconNetwork
		},
		{
			title: "Unified context API",
			description:
				"Single source of truth that powers all your AI workflows through one API. Scale from ten workflows to hundreds without fragmentation or engineering overhead.",
			icon: IconDatabase
		},
		{
			title: "Real-time data structuring",
			description:
				"Transform raw data into organized, linked context automatically. No tedious integrations or constant prompt engineering required.",
			icon: IconRefreshCw
		},
		{
			title: "Context-aware AI operations",
			description:
				"Your AI finally understands your business without manual prompt updates. Accurate, reliable operations that adapt as your data changes.",
			icon: IconBrain
		},
		{
			title: "Zero-friction integration",
			description:
				"Connect HubSpot, Notion, Google Drive, and workflow builders in minutes. Go from zero to production AI in days, not months.",
			icon: IconZap
		},
		{
			title: "Granular access control",
			description:
				"Enterprise-grade security with transparent, granular permissions. Control exactly what context each workflow can access.",
			icon: IconShieldCheck
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop losing time to fragmented context"
	subtitle="Start scaling AI workflows in days, not months"
	description="While your competitors scale AI operations, are you still manually updating prompts and fighting data silos? Join forward-thinking RevOps teams who eliminated engineering overhead and went from ten workflows to hundreds with unified context infrastructure."
	imageSrc="/generated/image-a-confident-operations-professional-age-.webp"
	callsToAction={[
		{
			href: "#get-started",
			label: "See Qontext in action",
			variant: "primary"
		},
		{
			href: "#contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
