VivaPortugal AI Content Automation Stack

End-to-end AI workflow for transforming raw product and travel photos into Pinterest-ready visual assets with SEO metadata and board-placement logic.

One image → premium visual → traffic-ready Pinterest pin.

This repository demonstrates how AI can automate the full Pinterest content pipeline — from raw visual input to long-term organic discovery.

Why it matters

Pinterest rewards consistent, high-quality vertical content, but producing it manually is slow, repetitive, and difficult to scale.

Creators and brands typically face three problems:

⏱️ Time — preparing visuals, crops, and metadata takes minutes per image

📉 SEO uncertainty — weak titles, descriptions, or wrong boards limit reach

🔁 Poor scalability — manual workflows don’t support daily publishing

This project shows how AI can replace fragmented tools with a single, automated, production-oriented workflow focused on long-term organic traffic — not short-term hacks or paid ads.

What this repository demonstrates

A two-layer AI workflow that can be reused across brands, products, and visual niches:

AI Product & Lifestyle Visual Generation

Pinterest Pin Optimization & Distribution Logic

Together, they form a practical AI content automation stack.

Layer 1 — AI Product & Lifestyle Visual Generation
Purpose

Transform a raw product photo into premium, Portuguese-themed lifestyle visuals without manual preparation or design work.

Workflow
1️⃣ Original product image (raw input)

Standard product photo

Can include lifestyle or human context (e.g. product worn by a model)

No background removal

No transparent PNG

No manual preparation

The image is treated as raw input.

2️⃣ Automatic product isolation & scene adaptation

The system automatically:

Identifies the primary product

Isolates it logically and visually

Prepares it for composition without user intervention

No visible masking or manual cleanup is required.

This removes the need for:

Manual background removal

External mockup tools

Photoshop-based workflows

3️⃣ AI-generated Portuguese lifestyle mockups

Using the isolated product, the system generates realistic lifestyle scenes inspired by Portugal.

Characteristics:

Soft Mediterranean daylight

Natural shadows

Calm, premium aesthetic

Multiple variations are generated:

Location

Mood

Lighting

Interior vs. outdoor scenes

Result: marketing-ready lifestyle visuals from a single raw image.

Layer 2 — Pinterest Pin Creator & SEO Optimizer
Purpose

Convert any visual (product mockup or travel photo) into a Pinterest-ready pin optimized for reach, saves, and long-term discovery.

What it does

Crops images to Pinterest-recommended 2:3 ratio (1000×1500)

Preserves key visual elements:

Main subject

Landmarks

Leading lines

Generates Pinterest-optimized metadata:

SEO title

Pin description

Hashtags

Recommends the most relevant Pinterest board using fixed decision logic

Output: a ready-to-publish Pinterest asset — no manual editing required.

End-to-End Flow (Product → Pinterest)

Raw product photo → automatic product isolation → AI lifestyle mockup generation → Pinterest 2:3 crop → SEO metadata → board recommendation → Pinterest-ready pin

The same Pinterest optimization layer is also used for:

Travel photography

Lifestyle imagery

Brand visuals

Use cases

Designed for professionals who rely on Pinterest as a long-term traffic channel:

Pinterest marketing specialists

Travel & lifestyle brands

Etsy & e-commerce sellers

Print-on-demand businesses

Content creators & photographers

Especially useful for daily or weekly publishing workflows.

Visual examples (recommended structure)

⚠️ Important: Do not overload the README.
4 images maximum is optimal.

1️⃣ Original input image

Raw product photo uploaded by the user.
No background removal, no manual preparation.

/screenshots/product_input.jpg

2️⃣ Automatic product isolation

The system isolates the product from the original photo automatically.
No external tools required.

This clean product asset is used internally for composition.

3️⃣ AI-generated Portuguese lifestyle mockups

The product is placed into realistic, Portugal-inspired lifestyle scenes.

Natural daylight

Soft shadows

Premium aesthetic

Multiple locations and moods

This replaces traditional mockup packs and Photoshop workflows.

/screenshots/lifestyle_mockups.jpg

4️⃣ Pinterest-ready pin (final output)

The selected mockup is converted into a fully optimized Pinterest pin.

2:3 ratio (1000×1500)

SEO title and description

Optimized hashtags

Pinterest board recommendation

Ready to publish without manual editing.

/screenshots/pinterest_pin_output.jpg

Technology overview

Google AI Studio (vision + text models)

Prompt-driven decision logic

Image processing enforcement (format & ratio)

Pinterest SEO and board-selection rules

No-code / low-code architecture

This repository focuses on workflow logic and results, not on training custom ML models.

Live context

This AI stack is actively used for:

VivaPortugal brand

Pinterest organic traffic experiments

Product and travel content automation

The workflows demonstrated here are platform-agnostic and can be adapted to other visual-first channels.

Key distinction

Unlike standalone mockup tools or caption generators, this system:

Accepts raw input images

Performs product isolation as part of the workflow

Generates marketing-ready visuals

Optimizes content specifically for Pinterest discovery

One input → one automated flow → one traffic-ready asset.

Built by Mikhail Gonnochenko
