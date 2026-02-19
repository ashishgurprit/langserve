# Skill-to-Module Dependency Map & Gap Analysis

> **Generated**: 2026-02-16
> **Scope**: 67 skills, 51 modules
> **Purpose**: Map all skill-to-module dependencies, identify orphans, missing references, and strategic gaps

---

## Table of Contents

1. [Dependency Matrix](#1-dependency-matrix)
2. [Module Usage Count](#2-module-usage-count)
3. [Orphan Modules](#3-orphan-modules)
4. [Missing Modules](#4-missing-modules)
5. [Gap Analysis](#5-gap-analysis)
6. [Skill Categories](#6-skill-categories)

---

## 1. Dependency Matrix

### Legend

- **M** = Module dependency (lives in `modules/`)
- **S** = Skill dependency (lives in `.claude/skills/`)
- **D** = Direct / required dependency
- **O** = Optional / related dependency

### New Skills (15) -- Module Dependencies

| Skill | unified-api-client | database-orm-patterns | scheduling-framework | content-pipeline-orchestrator | wordpress-publisher | social-media-client | omni-channel-core | image-optimizer | image-generation-validator | mobile-remote-config | mobile-form-validation | mobile-subscription | eas-deployment | supabase-database-setup | astro-blog-seo | decap-image-paste |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| google-analytics-search-console | D | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| crm-marketing-automation | D | D | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| affiliate-monetization | D | D | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| smart-content-scheduler | -- | D | D | D | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| stripe-subscription-billing | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | O | -- | -- | -- | -- |
| wix-app-framework | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| nextjs-app-patterns | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | D | -- |
| client-project-scaffolding | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | D | -- | -- |
| accessibility-wcag | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- |
| cms-headless-universal | -- | -- | -- | -- | D | -- | -- | D | -- | -- | -- | -- | -- | -- | D | D |
| migration-upgrade-patterns | -- | D | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | D | -- | -- | -- |
| responsive-email-templates | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| google-vertex-ai-imagen | D | -- | -- | -- | -- | -- | -- | D | D | -- | -- | -- | -- | -- | -- | -- |
| ecommerce-universal | D | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | O | -- | -- | -- | -- |
| conversion-rate-optimization | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- |

### New Skills (15) -- Skill Dependencies

| Skill | batch-processing | notification-universal | payment-processing-universal | auth-universal | background-jobs-universal | analytics-universal | rate-limiting-universal | email-universal | media-processing-universal | caching-universal | search-universal | seo-geo-aeo | wordpress-patterns | testing-strategies | e2e-testing | design-system | cicd-templates | deployment-patterns | deployment-lifecycle | pnpm-migration | security-owasp | performance | elite-frontend-developer | graphic-designer | visual-design-consultant | translation-pipeline | blog-content-writer | web-copywriter-fortune100 | database-patterns | api-patterns | google-analytics-search-console | railway-deployment |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| google-analytics-search-console | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| crm-marketing-automation | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| affiliate-monetization | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| smart-content-scheduler | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| stripe-subscription-billing | -- | D | D | O | -- | O | O | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| wix-app-framework | -- | -- | D | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | D | -- | -- |
| nextjs-app-patterns | -- | -- | -- | D | -- | -- | -- | -- | -- | D | -- | D | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | D |
| client-project-scaffolding | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | D | D | D | D | D | D | D | D | -- | -- | -- | -- | -- | D | D | -- | -- |
| accessibility-wcag | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | D | D | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| cms-headless-universal | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- |
| migration-upgrade-patterns | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | D | D | -- | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| responsive-email-templates | -- | D | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | D | D | -- | -- | -- | -- | -- | -- |
| google-vertex-ai-imagen | D | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| ecommerce-universal | -- | -- | D | D | D | D | -- | D | -- | D | D | D | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| conversion-rate-optimization | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | -- | -- | -- | -- | D | -- | -- | -- | -- | -- | D | -- | -- | D | -- |

### Existing Skills with Module References

| Skill | Module Dependencies |
|---|---|
| wordpress-patterns | (references `batch-processing` skill, `api-patterns` skill, `security-owasp` skill, `deployment-lifecycle` skill) |
| wordpress-seo-optimizer | `wordpress-publisher` (module) |
| firebase-auth-universal | `auth-universal` (skill reference) |
| railway-deployment | (references `api-patterns`, `security-owasp`, `deployment-lifecycle` skills) |

---

## 2. Module Usage Count

Modules sorted by how many skills reference them (higher = more foundational).

| Rank | Module | Referenced By (Skills) | Count |
|---|---|---|---|
| 1 | **unified-api-client** | google-analytics-search-console, crm-marketing-automation, affiliate-monetization, stripe-subscription-billing, wix-app-framework, google-vertex-ai-imagen, ecommerce-universal | **7** |
| 2 | **database-orm-patterns** | google-analytics-search-console, crm-marketing-automation, affiliate-monetization, smart-content-scheduler, stripe-subscription-billing, migration-upgrade-patterns | **6** |
| 3 | **wordpress-publisher** | smart-content-scheduler, cms-headless-universal, ecommerce-universal, wordpress-seo-optimizer | **4** |
| 4 | **content-pipeline-orchestrator** | affiliate-monetization, smart-content-scheduler | **2** |
| 4 | **scheduling-framework** | google-analytics-search-console, smart-content-scheduler | **2** |
| 4 | **eas-deployment** | client-project-scaffolding, migration-upgrade-patterns | **2** |
| 4 | **supabase-database-setup** | nextjs-app-patterns, client-project-scaffolding | **2** |
| 4 | **image-optimizer** | cms-headless-universal, google-vertex-ai-imagen | **2** |
| 4 | **mobile-remote-config** | migration-upgrade-patterns, conversion-rate-optimization | **2** |
| 4 | **astro-blog-seo** | nextjs-app-patterns, cms-headless-universal | **2** |
| 4 | **mobile-subscription** | stripe-subscription-billing, ecommerce-universal | **2** |
| 12 | **omni-channel-core** | crm-marketing-automation | **1** |
| 12 | **social-media-client** | smart-content-scheduler | **1** |
| 12 | **image-generation-validator** | google-vertex-ai-imagen | **1** |
| 12 | **decap-image-paste** | cms-headless-universal | **1** |
| 12 | **mobile-form-validation** | accessibility-wcag | **1** |
| 17 | agent-core | -- | **0** |
| 17 | audio-preprocessor | -- | **0** |
| 17 | dialogue-manager | -- | **0** |
| 17 | document-extractor | -- | **0** |
| 17 | entity-linker | -- | **0** |
| 17 | expo-push-notifications | -- | **0** |
| 17 | knowledge-synthesizer | -- | **0** |
| 17 | mobile-analytics | -- | **0** |
| 17 | mobile-app-update | -- | **0** |
| 17 | mobile-biometric-auth | -- | **0** |
| 17 | mobile-chat | -- | **0** |
| 17 | mobile-crash-reporting | -- | **0** |
| 17 | mobile-deep-linking | -- | **0** |
| 17 | mobile-haptics | -- | **0** |
| 17 | mobile-image-picker-upload | -- | **0** |
| 17 | mobile-localization | -- | **0** |
| 17 | mobile-maps-location | -- | **0** |
| 17 | mobile-network-status | -- | **0** |
| 17 | mobile-offline-first | -- | **0** |
| 17 | mobile-onboarding | -- | **0** |
| 17 | mobile-permissions | -- | **0** |
| 17 | mobile-secure-storage | -- | **0** |
| 17 | mobile-skeleton-loaders | -- | **0** |
| 17 | mobile-social-sharing | -- | **0** |
| 17 | prompt-library | -- | **0** |
| 17 | prompt-template-engine | -- | **0** |
| 17 | rag-pipeline | -- | **0** |
| 17 | react-native-theme | -- | **0** |
| 17 | speech-translate | -- | **0** |
| 17 | subtitle-sync | -- | **0** |
| 17 | supabase-mobile-auth | -- | **0** |
| 17 | supabase-realtime | -- | **0** |
| 17 | text-chunker | -- | **0** |
| 17 | voice-clone | -- | **0** |
| 17 | whisper-transcribe | -- | **0** |

### Skill-to-Skill Reference Count (Top Referenced Skills)

| Rank | Skill (referenced as dependency) | Referenced By | Count |
|---|---|---|---|
| 1 | **batch-processing** | google-analytics-search-console, crm-marketing-automation, affiliate-monetization, google-vertex-ai-imagen, wordpress-patterns | **5** |
| 2 | **deployment-patterns** | wix-app-framework, nextjs-app-patterns, client-project-scaffolding, migration-upgrade-patterns | **4** |
| 2 | **testing-strategies** | accessibility-wcag, client-project-scaffolding, migration-upgrade-patterns | **3** |
| 2 | **security-owasp** | client-project-scaffolding, migration-upgrade-patterns, wordpress-patterns, railway-deployment | **4** |
| 5 | **payment-processing-universal** | stripe-subscription-billing, wix-app-framework, ecommerce-universal | **3** |
| 5 | **auth-universal** | wix-app-framework, nextjs-app-patterns, ecommerce-universal, stripe-subscription-billing | **4** |
| 5 | **seo-geo-aeo** | nextjs-app-patterns, cms-headless-universal, ecommerce-universal, conversion-rate-optimization | **4** |
| 5 | **notification-universal** | crm-marketing-automation, stripe-subscription-billing, responsive-email-templates | **3** |
| 5 | **elite-frontend-developer** | nextjs-app-patterns, accessibility-wcag, client-project-scaffolding | **3** |
| 10 | **pnpm-migration** | client-project-scaffolding, migration-upgrade-patterns | **2** |
| 10 | **cicd-templates** | client-project-scaffolding, migration-upgrade-patterns | **2** |
| 10 | **deployment-lifecycle** | client-project-scaffolding, wordpress-patterns, railway-deployment | **3** |
| 10 | **email-universal** | responsive-email-templates, ecommerce-universal | **2** |
| 10 | **analytics-universal** | ecommerce-universal, conversion-rate-optimization, stripe-subscription-billing | **3** |
| 10 | **caching-universal** | nextjs-app-patterns, ecommerce-universal | **2** |
| 10 | **background-jobs-universal** | wix-app-framework, ecommerce-universal | **2** |

---

## 3. Orphan Modules

**35 modules** are NOT referenced by any skill's SKILL.md file. These are candidates for either:
- (a) Being wired into relevant skills via "Integrates With" sections
- (b) Having new skills created that consume them
- (c) Being deprecated if no longer useful

### AI / NLP Modules (7) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `agent-core` | Core agent framework | Could be consumed by a future `ai-agent-patterns` skill |
| `prompt-library` | Reusable prompt templates | `blog-content-writer`, `web-copywriter-fortune100`, `semantic-chunking` |
| `prompt-template-engine` | Prompt variable rendering engine | `blog-content-writer`, `universal-content-pipeline` |
| `rag-pipeline` | Retrieval-augmented generation | Future `ai-search-patterns` or `knowledge-base` skill |
| `text-chunker` | Text splitting for embeddings | `semantic-chunking` skill, `rag-pipeline` module |
| `knowledge-synthesizer` | Multi-source knowledge distillation | `universal-content-pipeline`, `blog-content-writer` |
| `entity-linker` | Named entity recognition and linking | `universal-content-pipeline`, `seo-geo-aeo` |

### Audio / Media Modules (5) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `audio-preprocessor` | Audio normalization and preprocessing | `media-processing-universal` skill |
| `speech-translate` | Speech-to-speech translation | `translation-pipeline` skill |
| `subtitle-sync` | Subtitle timing synchronization | `media-processing-universal` skill |
| `voice-clone` | Voice cloning / TTS | `media-processing-universal` skill |
| `whisper-transcribe` | OpenAI Whisper transcription | `media-processing-universal` skill, `translation-pipeline` |

### Dialogue Module (1) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `dialogue-manager` | Conversational state management | Future `chatbot-patterns` or `journaling-cbt-universal` skill |

### Document Module (1) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `document-extractor` | PDF/document text extraction | `pdf-processing` skill, `universal-content-pipeline` |

### Mobile Modules (16) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `mobile-analytics` | Mobile analytics tracking | `analytics-universal` skill, `app-store-optimization` |
| `mobile-app-update` | App update prompts | `app-store-optimization` skill |
| `mobile-biometric-auth` | FaceID/TouchID/fingerprint auth | `auth-universal` skill |
| `mobile-chat` | In-app chat implementation | Future `mobile-communication` skill |
| `mobile-crash-reporting` | Crash/error reporting | `performance` skill or future `mobile-observability` skill |
| `mobile-deep-linking` | Deep linking / universal links | `app-store-optimization` skill |
| `mobile-haptics` | Haptic feedback patterns | Future `mobile-ux-patterns` skill |
| `mobile-image-picker-upload` | Camera/gallery image selection | `media-processing-universal` skill |
| `mobile-localization` | i18n / l10n for mobile | `translation-pipeline` skill |
| `mobile-maps-location` | Maps and geolocation | Future `maps-geolocation` skill |
| `mobile-network-status` | Network reachability detection | `mobile-offline-first` (module, but no skill) |
| `mobile-offline-first` | Offline data sync patterns | Future `offline-first-patterns` skill |
| `mobile-onboarding` | Onboarding screens / flows | Future `mobile-ux-patterns` skill |
| `mobile-permissions` | Runtime permission handling | (Utility -- used implicitly by other mobile modules) |
| `mobile-secure-storage` | Keychain/Keystore secure storage | `auth-universal` skill, `mobile-biometric-auth` module |
| `mobile-skeleton-loaders` | Loading skeleton UI components | `design-system` skill |
| `mobile-social-sharing` | Native share sheet integration | Future `social-media-strategy` skill |

### Supabase Modules (2) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `supabase-mobile-auth` | Supabase Auth for React Native | `firebase-auth-universal` skill (could expand to `auth-universal`) |
| `supabase-realtime` | Supabase Realtime subscriptions | `websocket-universal` skill |

### Other Modules (2) -- No skill references

| Module | Purpose | Suggested Skill Consumer |
|---|---|---|
| `react-native-theme` | Theming system for React Native | `design-system` skill |
| `expo-push-notifications` | Expo push notification setup | `notification-universal` skill |

---

## 4. Missing Modules

References in skill SKILL.md files to modules/skills that either:
- Do not exist on the filesystem as modules, OR
- Are skills being referenced as if they were modules

### Skill References to Non-Existent Modules

| Referenced Name | Referenced By | Type on Filesystem | Status |
|---|---|---|---|
| `webhook-universal` | ecommerce-universal | Does NOT exist | **MISSING** -- Consider creating or folding into `background-jobs-universal` |

### Notes on Type Mismatches

The following are referenced in dependency diagrams but exist as **skills**, not **modules**. This is not a bug -- skills can depend on other skills -- but is worth noting for architectural clarity:

| Name | Referenced By | Exists As |
|---|---|---|
| `batch-processing` | google-analytics-search-console, crm-marketing-automation, affiliate-monetization, google-vertex-ai-imagen | **Skill** (not module) |
| `notification-universal` | crm-marketing-automation, stripe-subscription-billing, responsive-email-templates | **Skill** (not module) |
| `payment-processing-universal` | stripe-subscription-billing, wix-app-framework, ecommerce-universal | **Skill** (not module) |
| `auth-universal` | wix-app-framework, nextjs-app-patterns, ecommerce-universal | **Skill** (not module) |
| `background-jobs-universal` | wix-app-framework, ecommerce-universal | **Skill** (not module) |
| `media-processing-universal` | google-vertex-ai-imagen | **Skill** (not module) |
| `analytics-universal` | stripe-subscription-billing, ecommerce-universal, conversion-rate-optimization | **Skill** (not module) |
| `email-universal` | responsive-email-templates, ecommerce-universal | **Skill** (not module) |
| `search-universal` | ecommerce-universal | **Skill** (not module) |
| `caching-universal` | nextjs-app-patterns, ecommerce-universal | **Skill** (not module) |
| `rate-limiting-universal` | stripe-subscription-billing | **Skill** (not module) |

---

## 5. Gap Analysis

### High-Impact Module Gaps

These are modules that, if created, would serve the most skills and fill the largest dependency voids.

#### Priority 1: Modules That Would Serve 5+ Skills

| Proposed Module | Would Serve Skills | Rationale |
|---|---|---|
| **`feature-flags`** | conversion-rate-optimization, migration-upgrade-patterns, mobile-remote-config (enhance), stripe-subscription-billing, ecommerce-universal, wix-app-framework | Feature flags are referenced across CRO, migrations, billing, and A/B testing. A unified module would consolidate patterns currently scattered across `mobile-remote-config` and ad-hoc code. |
| **`webhook-handler`** | ecommerce-universal, stripe-subscription-billing, wix-app-framework, crm-marketing-automation, smart-content-scheduler | Webhook signature verification, idempotency, and retry are reimplemented in every skill. A shared module would DRY this up. Currently referenced as `webhook-universal` (missing). |

#### Priority 2: Modules That Would Serve 3-4 Skills

| Proposed Module | Would Serve Skills | Rationale |
|---|---|---|
| **`csv-data-processor`** | affiliate-monetization, google-vertex-ai-imagen, crm-marketing-automation, google-analytics-search-console | CSV reading, validation, chunking, and progress tracking appear across batch scraping, image generation, CRM imports, and analytics export. |
| **`google-auth-provider`** | google-analytics-search-console, google-vertex-ai-imagen, cms-headless-universal (Sheets-backed) | Google service account authentication, OAuth2, and credential management is duplicated across GA, Vertex AI, and Drive skills. |
| **`queue-manager`** | smart-content-scheduler, google-vertex-ai-imagen, crm-marketing-automation, affiliate-monetization | Priority queue, rate-limited processing, checkpoint/resume. Currently each skill reimplements queue logic. |

#### Priority 3: Skills That Would Wire In Orphan Modules

| Proposed Skill | Modules It Would Consume | Impact |
|---|---|---|
| **`ai-agent-patterns`** | agent-core, prompt-library, prompt-template-engine, rag-pipeline, text-chunker, knowledge-synthesizer, entity-linker, document-extractor | Would give purpose to **8 orphan modules** -- the entire AI/NLP suite. Covers building AI agents, RAG pipelines, prompt engineering, and knowledge extraction. |
| **`mobile-ux-patterns`** | mobile-haptics, mobile-onboarding, mobile-skeleton-loaders, mobile-permissions, react-native-theme | Would consume **5 orphan modules** focused on mobile user experience. |
| **`audio-media-pipeline`** | audio-preprocessor, whisper-transcribe, speech-translate, subtitle-sync, voice-clone | Would consume **5 orphan modules** focused on audio processing. Covers transcription, translation, subtitle sync, and voice cloning. |
| **`mobile-communication`** | mobile-chat, expo-push-notifications, mobile-social-sharing, mobile-deep-linking | Would consume **4 orphan modules** for in-app messaging, push notifications, sharing, and deep links. |
| **`mobile-resilience`** | mobile-offline-first, mobile-network-status, mobile-crash-reporting, mobile-app-update | Would consume **4 orphan modules** focused on mobile app stability and connectivity. |

### Wiring Recommendations for Existing Skills

These orphan modules could be added to existing skill "Integrates With" sections without creating new skills:

| Orphan Module | Best Existing Skill to Wire Into | How |
|---|---|---|
| `expo-push-notifications` | `notification-universal` | Add as mobile push provider alongside email/SMS/webhooks |
| `mobile-analytics` | `analytics-universal` | Add as mobile analytics layer (Firebase Analytics, Mixpanel mobile) |
| `mobile-biometric-auth` | `auth-universal` | Add as biometric authentication factor |
| `mobile-secure-storage` | `auth-universal` | Add for token/credential storage on mobile |
| `supabase-mobile-auth` | `firebase-auth-universal` or `auth-universal` | Add as Supabase alternative to Firebase Auth on mobile |
| `supabase-realtime` | `websocket-universal` | Add as Supabase-specific WebSocket provider |
| `react-native-theme` | `design-system` | Add as React Native theming implementation |
| `mobile-skeleton-loaders` | `design-system` | Add as loading state components |
| `mobile-localization` | `translation-pipeline` | Add as mobile i18n implementation |
| `document-extractor` | `pdf-processing` | Add as document extraction backend |
| `prompt-library` | `blog-content-writer` or `universal-content-pipeline` | Add as prompt template source |
| `prompt-template-engine` | `universal-content-pipeline` | Add as variable rendering engine for content generation |
| `mobile-image-picker-upload` | `media-processing-universal` | Add as mobile media source |
| `mobile-deep-linking` | `app-store-optimization` | Add for deep link setup and ASO |
| `mobile-app-update` | `app-store-optimization` | Add for update prompt best practices |

---

## 6. Skill Categories

### Marketing & Growth (10 skills)

| Skill | Key Module Dependencies |
|---|---|
| google-analytics-search-console | unified-api-client, database-orm-patterns, scheduling-framework |
| crm-marketing-automation | unified-api-client, database-orm-patterns, omni-channel-core |
| affiliate-monetization | unified-api-client, database-orm-patterns, content-pipeline-orchestrator |
| conversion-rate-optimization | mobile-remote-config |
| seo-geo-aeo | (no module deps documented) |
| app-store-optimization | (no module deps documented) |
| linkedin-viral-posts | (no module deps documented) |
| youtube-advertising | (no module deps documented) |
| web-copywriter-fortune100 | (no module deps documented) |
| smart-content-scheduler | scheduling-framework, wordpress-publisher, content-pipeline-orchestrator, database-orm-patterns, social-media-client |

### E-Commerce & Payments (3 skills)

| Skill | Key Module Dependencies |
|---|---|
| ecommerce-universal | unified-api-client, wordpress-publisher, mobile-subscription |
| stripe-subscription-billing | unified-api-client, database-orm-patterns, mobile-subscription |
| payment-processing-universal | (no module deps documented) |

### Content & Publishing (6 skills)

| Skill | Key Module Dependencies |
|---|---|
| cms-headless-universal | wordpress-publisher, image-optimizer, astro-blog-seo, decap-image-paste |
| blog-content-writer | (no module deps documented) |
| potentialz-blog-writer | (no module deps documented) |
| universal-content-pipeline | (no module deps documented) |
| responsive-email-templates | (no module deps -- skill-only refs) |
| semantic-chunking | (no module deps documented) |

### Frontend & Web Development (7 skills)

| Skill | Key Module Dependencies |
|---|---|
| nextjs-app-patterns | supabase-database-setup, astro-blog-seo |
| elite-frontend-developer | (no module deps documented) |
| design-system | (no module deps documented) |
| accessibility-wcag | mobile-form-validation |
| performance | (no module deps documented) |
| wix-app-framework | unified-api-client |
| wordpress-patterns | (no module deps documented) |

### DevOps & Infrastructure (8 skills)

| Skill | Key Module Dependencies |
|---|---|
| client-project-scaffolding | eas-deployment, supabase-database-setup |
| migration-upgrade-patterns | database-orm-patterns, mobile-remote-config, eas-deployment |
| cicd-templates | (no module deps documented) |
| deployment-patterns | (no module deps documented) |
| deployment-lifecycle | (no module deps documented) |
| railway-deployment | (no module deps documented) |
| pnpm-migration | (no module deps documented) |
| website-security-hardening | (no module deps documented) |

### Mobile Development (1 skill + modules)

| Skill | Key Module Dependencies |
|---|---|
| app-store-optimization | (no module deps documented) |
| *Note*: 20+ mobile modules exist but only 3 are referenced by any skill | |

### AI & Image Generation (2 skills)

| Skill | Key Module Dependencies |
|---|---|
| google-vertex-ai-imagen | unified-api-client, image-optimizer, image-generation-validator |
| graphic-designer | (no module deps documented) |
| visual-design-consultant | (no module deps documented) |

### Security & Quality (4 skills)

| Skill | Key Module Dependencies |
|---|---|
| security-owasp | (no module deps documented) |
| testing-strategies | (no module deps documented) |
| e2e-testing | (no module deps documented) |
| website-seo-optimizer | wordpress-publisher |

### Authentication (2 skills)

| Skill | Key Module Dependencies |
|---|---|
| auth-universal | (no module deps documented) |
| firebase-auth-universal | (no module deps documented) |

### Backend & API (6 skills)

| Skill | Key Module Dependencies |
|---|---|
| api-patterns | (no module deps documented) |
| database-patterns | (no module deps documented) |
| background-jobs-universal | (no module deps documented) |
| batch-processing | (no module deps documented -- it IS the skill consumed by others) |
| caching-universal | (no module deps documented) |
| rate-limiting-universal | (no module deps documented) |

### Communication & Notifications (5 skills)

| Skill | Key Module Dependencies |
|---|---|
| email-universal | (no module deps documented) |
| sms-universal | (no module deps documented) |
| notification-universal | (no module deps documented) |
| websocket-universal | (no module deps documented) |
| file-upload-universal | (no module deps documented) |

### Search & Data (2 skills)

| Skill | Key Module Dependencies |
|---|---|
| search-universal | (no module deps documented) |
| pdf-processing | (no module deps documented) |

### Strategy & Planning (3 skills)

| Skill | Key Module Dependencies |
|---|---|
| strategic-plan | (no module deps documented) |
| journaling-cbt-universal | (no module deps documented) |
| admin-business-ops-universal | (no module deps documented) |

### Platform-Specific Practices (3 skills)

| Skill | Key Module Dependencies |
|---|---|
| atlassian-practices | (no module deps documented) |
| google-engineering | (no module deps documented) |
| canva-practices | (no module deps documented) |

### Content & Media Processing (3 skills)

| Skill | Key Module Dependencies |
|---|---|
| media-processing-universal | (no module deps documented) |
| translation-pipeline | (no module deps documented) |
| multi-provider-pattern | (no module deps documented) |

---

## Summary Statistics

| Metric | Value |
|---|---|
| Total skills | 67 |
| Total modules | 51 |
| Modules referenced by at least 1 skill | **16** (31%) |
| Modules with 0 skill references (orphans) | **35** (69%) |
| Most-referenced module | `unified-api-client` (7 skills) |
| Most-referenced skill (as dependency) | `batch-processing` (5 skills) |
| Missing module references | 1 (`webhook-universal`) |
| New modules proposed (Priority 1-2) | 5 |
| New skills proposed to consume orphans | 5 (would cover 26 orphan modules) |
| Existing skill wiring recommendations | 15 (would cover remaining 9 orphan modules) |

### Key Takeaway

The ecosystem has a strong core of foundational modules (`unified-api-client`, `database-orm-patterns`, `scheduling-framework`) that are well-connected. However, **69% of modules are orphaned** -- particularly the mobile (16 modules), AI/NLP (7 modules), and audio (5 modules) clusters. Creating 3-5 new skills (`ai-agent-patterns`, `mobile-ux-patterns`, `audio-media-pipeline`, `mobile-communication`, `mobile-resilience`) and wiring 15 orphan modules into existing skills would achieve near-complete coverage.
