# Awesome Shopify [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Shopify resources — APIs, SDKs, developer tools, themes, apps, headless frameworks and learning materials for merchants, developers and agencies.

Everything for building on and selling with [Shopify](https://www.shopify.com) — from the Admin and Storefront APIs to Hydrogen, Liquid themes, checkout extensions, and the new AI shopping agents built on Shopify's MCP. Maintained by the team behind [Mention Network](https://mention.network); see also [awesome-agentic-commerce](https://github.com/MentionNetwork/awesome-agentic-commerce).

## Contents

- [Official Resources](#official-resources)
- [APIs & SDKs](#apis--sdks)
- [CLI & Developer Tools](#cli--developer-tools)
- [App Development](#app-development)
- [Theme Development](#theme-development)
- [Headless & Hydrogen](#headless--hydrogen)
- [AI, MCP & Agents](#ai-mcp--agents)
- [Payments & Checkout](#payments--checkout)
- [Top Apps](#top-apps)
- [Learning Resources](#learning-resources)
- [Communities](#communities)
- [Podcasts & Newsletters](#podcasts--newsletters)
- [Top Articles & Guides](#top-articles--guides)

## Official Resources

- [Shopify Developer Changelog](https://shopify.dev/changelog) - Chronological log of all platform, API and feature changes for developers.
- [Shopify Developer Docs](https://shopify.dev) - Central developer platform for building apps, custom storefronts and themes.
- [Shopify Engineering Blog](https://shopify.engineering) - Deep technical posts on scaling, Ruby, React Native and AI from Shopify's engineering team.
- [Shopify Help Center](https://help.shopify.com) - Merchant-facing help covering store setup, orders, payments and POS.
- [Shopify Status](https://www.shopifystatus.com) - Official system status page reporting uptime and incidents.

## APIs & SDKs

- [Admin API GraphiQL Explorer](https://shopify.dev/docs/api/usage/api-exploration/admin-graphiql-explorer) - In-browser tool for writing, validating and testing Admin API GraphQL queries.
- [Admin GraphQL API](https://shopify.dev/docs/api/admin-graphql) - Primary GraphQL API for building apps and integrations that extend the Shopify admin.
- [shopify-api-ruby](https://github.com/Shopify/shopify-api-ruby) - Official Ruby gem providing REST and GraphQL access to the Admin API plus webhooks.
- [shopify-app-js](https://github.com/Shopify/shopify-app-js) - Official monorepo of JavaScript/TypeScript packages for Shopify APIs and app building.
- [shopify_python_api](https://github.com/Shopify/shopify_python_api) - Official Python library for the Shopify Admin API.
- [Storefront API](https://shopify.dev/docs/api/storefront) - GraphQL API providing commerce primitives for custom, headless shopping experiences.

## CLI & Developer Tools

- [Shopify CLI](https://github.com/Shopify/cli) - Official command-line tool to build apps, themes and Hydrogen storefronts.
- [Shopify Functions](https://shopify.dev/docs/apps/build/functions) - Serverless backend logic to customize business logic such as discounts and checkout.
- [Shopify Polaris](https://polaris.shopify.com) - Shopify's design system and component guidance for building admin app UIs.
- [Shopify theme-tools](https://github.com/Shopify/theme-tools) - Parsers, formatters, linters (Theme Check) and language servers for Liquid theme development.
- [Shopify UI Extensions](https://github.com/Shopify/ui-extensions) - Public definitions for the UI extension APIs used to build checkout and admin extensions.

## App Development

- [BestAppify](https://bestappify.com) - Marketing platform for Shopify app developers: rank tracking, listing optimizer with AI audit, competitor watch, review intelligence, and a public catalogue of ~26,700 live Shopify apps.
- [Shopify App Bridge](https://shopify.dev/docs/api/app-bridge) - JavaScript SDK letting embedded apps communicate with and render inside the Shopify admin.
- [Shopify App Template (React Router)](https://github.com/Shopify/shopify-app-template-react-router) - Official template for embedded apps with React Router v7+, the recommended starting point.
- [Shopify App Template (Remix)](https://github.com/Shopify/shopify-app-template-remix) - Official Remix-based app template (now superseded by the React Router template).

## Theme Development

- [Dawn](https://github.com/Shopify/dawn) - Shopify's source-available reference theme with Online Store 2.0 features and built-in performance.
- [Horizon](https://github.com/Shopify/horizon) - Source for Shopify's Horizon theme, the newer default with AI-assisted design blocks.
- [Liquid Reference](https://shopify.dev/docs/api/liquid) - Reference for the Liquid tags, filters and objects used to build Shopify themes.
- [Skeleton Theme](https://github.com/Shopify/skeleton-theme) - Minimal, best-practice starter theme for building a Shopify theme from scratch.
- [Theme Architecture (Online Store 2.0)](https://shopify.dev/docs/storefronts/themes/architecture) - Documentation of theme file structure, layouts, templates, sections and blocks.

## Headless & Hydrogen

- [Hydrogen](https://github.com/Shopify/hydrogen) - Shopify's React framework for building headless commerce storefronts, built on React Router.
- [Hydrogen Docs](https://shopify.dev/docs/api/hydrogen) - Official documentation for Hydrogen, Shopify's opinionated headless stack.
- [Next.js Commerce](https://github.com/vercel/commerce) - High-performance Next.js ecommerce starter maintained by Vercel with Shopify as its primary backend.
- [Oxygen](https://shopify.dev/docs/custom-storefronts/oxygen) - Shopify's global hosting platform for deploying Hydrogen storefronts via the CLI.
- [React Router (Remix)](https://reactrouter.com) - React framework (formerly Remix) underpinning Hydrogen and Shopify's app templates.

## AI, MCP & Agents

- [BestAppify MCP](https://bestappify.com/mcp) - 59-tool MCP server for Shopify App Store data. Read + write tools (track keywords, propose listing rewrites, render screenshots). Open-source [agent skills on GitHub](https://github.com/rezzarzk/bestappify-agent-skills).
- [Build a Storefront AI Agent](https://shopify.dev/docs/apps/build/storefront-mcp/build-storefront-ai-agent) - Step-by-step guide to building a storefront AI shopping agent on Shopify's MCP tools.
- [Shopify Dev MCP](https://shopify.dev/docs/apps/build/devmcp) - Shopify's developer MCP server and AI toolkit letting coding assistants query Shopify docs and APIs.
- [Shopify Storefront MCP](https://shopify.dev/docs/apps/build/storefront-mcp) - Model Context Protocol interface exposing a store's catalog, cart and policies to AI shopping agents.
- [shop-chat-agent](https://github.com/Shopify/shop-chat-agent) - Official reference app for an AI storefront chat agent using Shopify's MCP tools.
- [Storefront MCP Server Reference](https://shopify.dev/docs/apps/build/storefront-mcp/servers/storefront) - Reference detailing the Storefront MCP server tools such as get_cart and catalog search.

## Payments & Checkout

- [Checkout Extensibility](https://shopify.dev/docs/apps/build/checkout) - Guide to augmenting Shopify checkout with new functionality by building apps with extensions.
- [Checkout UI Extensions](https://shopify.dev/docs/api/checkout-ui-extensions) - API for adding custom UI and logic into any step of the Shopify checkout.
- [Payments Extensions](https://shopify.dev/docs/apps/build/payments) - Developer documentation for building payments extensions that process payments during checkout.
- [Shopify Payments](https://help.shopify.com/en/manual/payments/shopify-payments) - Merchant help documentation for activating and managing Shopify Payments.

## Top Apps

Popular, highly-rated apps from the [Shopify App Store](https://apps.shopify.com), grouped by use case.

### Email & SMS Marketing

- [Klaviyo](https://apps.shopify.com/klaviyo-email-marketing) - Email, SMS and WhatsApp marketing platform with segmentation and automation built on customer data.
- [Omnisend](https://apps.shopify.com/omnisend) - Combines email marketing, newsletters, SMS and popups to drive ecommerce sales.
- [Postscript](https://apps.shopify.com/postscript-sms-marketing) - SMS marketing platform for campaigns, automations and cart-recovery texts.
- [Privy](https://apps.shopify.com/privy) - Grows email and SMS lists with popups and sends automated marketing messages.
- [Shopify Email](https://apps.shopify.com/shopify-email) - Native Shopify email and SMS marketing tool for creating branded campaigns in one place.

### Reviews & UGC

- [Judge.me](https://apps.shopify.com/judgeme) - Collects and displays unlimited product reviews, photos, videos and star ratings.
- [Loox](https://apps.shopify.com/loox) - Captures visual product reviews with photo and video UGC to boost conversions.
- [Okendo](https://apps.shopify.com/okendo-reviews) - Reviews, loyalty, referrals and quizzes platform for building customer trust.
- [Stamped](https://apps.shopify.com/product-reviews-addon) - Gathers product reviews, ratings, photos and Q&A alongside loyalty features.
- [Yotpo](https://apps.shopify.com/yotpo-social-reviews) - Collects and displays product reviews and ratings to showcase social proof.

### Upsell & Cross-sell

- [Candy Rack](https://apps.shopify.com/candyrack) - All-in-one upsell and cross-sell app with AI recommendations and a built-in cart drawer.
- [Frequently Bought Together](https://apps.shopify.com/frequently-bought-together) - Adds smart frequently-bought-together bundle recommendations to product pages.
- [ICU In Cart Upsell](https://apps.shopify.com/in-cart-upsell) - Shows in-cart, cross-sell and post-purchase upsell offers to lift order value.
- [ReConvert](https://apps.shopify.com/reconvert-upsell-cross-sell) - Builds cart, checkout and post-purchase upsell funnels to raise average order value.

### Loyalty & Rewards

- [BON Loyalty](https://apps.shopify.com/bon-loyalty-rewards) - Runs points, VIP tiers and referral rewards programs to boost retention.
- [Growave](https://apps.shopify.com/growave) - All-in-one retention suite combining loyalty, reviews and wishlists.
- [LoyaltyLion](https://apps.shopify.com/loyaltylion) - Loyalty platform with points, tiers and referrals to drive repeat purchases.
- [Smile](https://apps.shopify.com/smile-io) - Launches points, VIP tiers and referral loyalty programs to reward repeat customers.

### Subscriptions

- [Appstle](https://apps.shopify.com/subscriptions-by-appstle) - Powers subscriptions, subscription boxes and bundles for recurring revenue.
- [Loop Subscriptions](https://apps.shopify.com/loop-subscriptions) - Manages subscriptions at scale with customer portals and churn-reduction tools.
- [Recharge](https://apps.shopify.com/subscription-payments) - Subscription platform for recurring billing, customer portals and churn prevention.
- [Seal Subscriptions](https://apps.shopify.com/seal-subscriptions) - Adds subscriptions and memberships with flexible recurring order options.

### Page Builders

- [EComposer](https://apps.shopify.com/ecomposer) - Drag-and-drop builder for any Shopify page with AI tools and CRO add-ons.
- [GemPages](https://apps.shopify.com/gempages) - AI-powered page builder for conversion-focused landing pages and sales funnels.
- [PageFly](https://apps.shopify.com/pagefly) - Drag-and-drop page builder for CRO-focused landing, product and home pages.
- [Shogun](https://apps.shopify.com/shogun) - Visual editor for building blog posts, product pages, landing pages and sections.

### SEO

- [Avada SEO](https://apps.shopify.com/avada-seo-suite) - AI SEO suite with audits, on-page optimization and image compression.
- [SearchPie](https://apps.shopify.com/seo-booster) - SEO booster with speed optimization, schema markup and bulk AI meta tags.
- [Smart SEO](https://apps.shopify.com/smart-seo) - Improves SEO through meta tags, structured data and page-speed optimization.
- [Tiny SEO](https://apps.shopify.com/smart-image-optimizer) - Optimizes images, alt text, page speed and SEO schema for better rankings.

### Search & Filters

- [Algolia AI Search](https://apps.shopify.com/algolia-search) - Enterprise AI search and discovery for higher conversions at scale.
- [Boost AI Search](https://apps.shopify.com/product-filter-search) - AI-powered search bar, product filters and merchandising for discovery.
- [Shopify Search & Discovery](https://apps.shopify.com/search-and-discovery) - Native Shopify app to customize storefront search, filters and recommendations.
- [Smart Product Filter & Search](https://apps.shopify.com/smart-product-filter) - Adds AI semantic search and instant collection filters to product discovery.

### Customer Support & Chat

- [Gorgias](https://apps.shopify.com/helpdesk) - Ecommerce helpdesk unifying email, chat and social with AI-powered automation.
- [Re:amaze](https://apps.shopify.com/reamaze) - AI-powered helpdesk and live chat unifying support across multiple channels.
- [Shopify Inbox](https://apps.shopify.com/inbox) - Native Shopify chat with an AI sales associate for storefront conversations.
- [Tidio](https://apps.shopify.com/tidio-chat) - Live chat and AI chatbot for instant shopper support and sales.

### Shipping & Fulfillment

- [AfterShip](https://apps.shopify.com/aftership) - Branded order tracking and shipment notifications across 1,100+ carriers.
- [Easyship](https://apps.shopify.com/easyship) - Compares shipping rates and automates labels, tracking and duties.
- [ParcelPanel](https://apps.shopify.com/parcelpanel) - Order tracking with branded tracking pages to reduce WISMO inquiries.
- [ShipStation](https://apps.shopify.com/shipstation) - Shipping and fulfillment platform with multi-carrier label automation.

### Analytics & Reporting

- [Better Reports](https://apps.shopify.com/betterreports) - Custom reporting and analytics to explore and export store data.
- [Lucky Orange](https://apps.shopify.com/lucky-orange) - Heatmaps, session recordings and analytics to spot friction and lift conversions.
- [Report Pundit](https://apps.shopify.com/report-pundit) - Builds custom reports, combines data sources and automates delivery.
- [Triple Whale](https://apps.shopify.com/triplewhale-1) - Centralizes ecommerce analytics and marketing attribution with AI insights.

### Print-on-Demand & Sourcing

- [DSers](https://apps.shopify.com/dsers) - AliExpress dropshipping tool for product importing and bulk order fulfillment.
- [Printful](https://apps.shopify.com/printful) - Prints and ships custom apparel and products on demand with no upfront cost.
- [Printify](https://apps.shopify.com/printify) - Creates and sells custom products through a global print-on-demand network.
- [Spocket](https://apps.shopify.com/spocket) - Sources dropshipping products from verified US and EU suppliers.

## Learning Resources

- [Liquid Storefronts for Theme Developers](https://www.shopifyacademy.com/path/liquid-storefronts-for-theme-developers) - Structured Shopify Academy learning path teaching theme development with Liquid.
- [Shopify Academy](https://www.shopifyacademy.com) - Free courses and credential assessments across selling, marketing and store building.
- [Shopify Learn](https://www.shopify.com/learn) - Free educational hub of guided courses and tutorials for merchants and developers.
- [Shopify Partners Blog](https://www.shopify.com/partners/blog) - Blog for developers and agencies on app development, theme development and growing a practice.

## Communities

- [r/shopify](https://www.reddit.com/r/shopify/) - Large Reddit community for Shopify merchants, developers and partners.
- [Shopify Community Forums](https://community.shopify.com) - Official forums where merchants and partners discuss stores, apps, themes and marketing.
- [Shopify Developer Community](https://community.shopify.dev) - Space for developers building on Shopify to get help and discuss APIs and dev tools.
- [Shopify Partners](https://www.shopify.com/partners) - Official program for developers, agencies and freelancers building on the platform.

## Podcasts & Newsletters

- [eCommerce Fastlane](https://ecommercefastlane.com) - Shopify-focused podcast and blog by Steve Hutt blending founder, agency and platform insights.
- [Future Commerce](https://www.futurecommerce.com) - Commerce media brand publishing a podcast, research and newsletters for retail leaders.
- [Shopify Masters](https://shopify-masters.simplecast.com) - Official Shopify podcast interviewing entrepreneurs about building and growing their stores.
- [The Unofficial Shopify Podcast](https://unofficialshopifypodcast.com) - Long-running weekly show by Kurt Elster on Shopify store strategy, apps and ecosystem changes.

## Top Articles & Guides

- [Clustering Billions of Products for Agentic Commerce](https://shopify.engineering/catalog-clustering) - Shopify Engineering, 2026. How Shopify clusters billions of products to power its Catalog API.
- [Five Years of React Native at Shopify](https://shopify.engineering/five-years-of-react-native-at-shopify) - Shopify Engineering, 2025. Retrospective on a five-year React Native bet across productivity and performance.
- [Flow Generation Through Natural Language](https://shopify.engineering/fine-tuning-agent-shopify-flow) - Shopify Engineering, 2026. Agentic modeling approach to generating Shopify Flow automations from natural language.
- [Introducing Theme Blocks in Developer Preview](https://www.shopify.com/partners/blog/themeblocks) - Shopify Partners, 2024. Previews theme blocks and the layout flexibility coming to Online Store themes.
- [Migrating to React Native's New Architecture](https://shopify.engineering/react-native-new-architecture) - Shopify Engineering, 2025. Deep dive into the migration and its animation and frame-rate challenges.
- [Quick: An Internal Hosting Platform for the AI Era](https://shopify.engineering/quick) - Shopify Engineering, 2026. Introduces Quick, Shopify's internal hosting platform for AI-era workloads.
- [Replacing Redis with MySQL for Inventory Reservations](https://shopify.engineering/scaling-inventory-reservations) - Shopify Engineering, 2026. Case study on re-architecting inventory reservations and how it scaled.
- [Shopify Customization: 5 Ways to Customize Themes](https://www.shopify.com/blog/customizing-store-theme) - Shopify, 2025. Merchant-facing guide to five ways of customizing a store theme.
- [Teaching Sidekick to Say No](https://shopify.engineering/sidekick-curation) - Shopify Engineering, 2026. Automated data curation with LLM-judge consensus to improve the Sidekick AI assistant.

## Contributing

Contributions are welcome! Read the [contribution guidelines](contributing.md) first.
