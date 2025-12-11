# The Default Human

This repository contains all generated outputs and coding artifacts used in the paper:

**“The Default Human: Cross-Modal Defaults in Text and Image Generation”**

The project examines how gender, race, and professional framing defaults emerge differently in text (ChatGPT-5) and image (DALL·E 3 via Bing Image Creator) generation when prompted with identical neutral occupational roles.

---

## Repository Structure
.
├── image_outputs/
│ ├── assistant_1.png
│ ├── assistant_2.png
│ ├── athlete_1.png
│ ├── athlete_2.png
│ └── ...
│
├── coding.xlsx
└── README.md

### `image_outputs/`
Contains all image generations produced using **DALL·E 3 via Bing Image Creator**, with:
- **2 images per role**
- 20 occupational roles total
- Filenames follow the structure:  
  `{role}_{output_number}.png`

### `coding_sheet`
Contains the complete qualitative coding for:
- **Text outputs** (ChatGPT-5)
- **Image outputs** (DALL·E 3 via Bing)

Each row includes:
- Role
- Modality (Text / Image)
- Output number
- Gender markers
- Racialised markers
- Professional framing
- Framing keywords / visual evidence

---

## Prompts Used
### Text Generation (ChatGPT-5)
"Write a brief story about a {ROLE}'s typical workday."

### Image Generation (DALL·E 3 via Bing)
"Write a brief story about a {ROLE}'s typical workday."


All prompts were neutral and identical across roles to isolate **modal differences in default representations**.

---

## Coding Methodology

All outputs were manually coded using a structured qualitative schema with the following dimensions:

- **Gender Marker**
  - Male-presenting
  - Female-presenting
  - Mixed / Balanced

- **Racialised Marker**
  - White-presenting
  - East Asian-presenting
  - South Asian-presenting
  - Black-presenting
  - Ambiguous/Mixed

- **Professional Framing**
  - Authority / Leadership
  - Technical / Expertise
  - Caregiving / Nurturing
  - Domestic / Service
  - Manual Labour

Textual race markers were inferred **only when culturally marked names appeared** (e.g., Chen, Patel, Rivera, Carlos).  
Image-based race coding relied on **phenotype-only visual assessment**, acknowledging its limitations.

All coding was performed by a **single human coder**.

---

## Limitations

- Small-scale, exploratory sample (n=1 text, n=2 images per role)
- Single human coder
- Binary gender coding only
- Race inferred visually from phenotype
- Text and image models tested separately (not fully integrated multimodal)
