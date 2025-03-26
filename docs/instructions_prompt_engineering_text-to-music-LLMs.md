# Text-to-Music Prompt Engineering Guide for Suno.com

## Creating Effective Initial Prompts (200 Character Limit)

### Core Prompt Structure
Your initial 200-character prompt should follow this formula:

```
[Genre] + [Mood/Emotion] + [Key Musical Element] + [Reference or Inspiration] + [Purpose/Context]
```

### Step-by-Step Prompt Construction

1. **Choose your primary genre** (10-15 chars)
   - Be specific: "Lo-fi hip-hop" > "Hip-hop"
   - For fusion styles, put dominant genre first: "Jazz-rock fusion with electronic elements"

2. **Define the mood or emotion** (20-30 chars)
   - Use vivid emotional descriptors: "melancholic but hopeful" > "sad"
   - Connect emotion to context: "joyful celebration of summer"

3. **Specify key musical elements** (40-60 chars)
   - Tempo: "fast-paced" or "slow and deliberate" or specific BPM
   - Instrumentation: "prominently featuring violin and piano"
   - Structure: "with a dramatic bridge section"
   - Vocal style: "ethereal female vocals with harmonies"

4. **Add reference points** (30-50 chars)
   - Artists: "in the style of [Artist]"
   - Era: "reminiscent of early 90s Seattle grunge"
   - Specific song: "with chord progressions similar to [Song]"

5. **Include purpose/context** (30-50 chars)
   - "for studying" or "for an emotional film scene"
   - "for dancing" or "for background at a café"

### Sample Prompt Templates

**For Casual Music Listeners:**
```
[Genre] song with [emotional quality] feel. Features [instrument] and [vocal description]. Similar to [popular artist/song], perfect for [activity].
```

**For Technical Musicians:**
```
[Genre] in [key] at [tempo]. [Instrument] leads with [technique]. [Harmony type] chord progression. Inspired by [artist], suited for [context].
```

**For Genre Specialists:**
```
Authentic [subgenre] with traditional [element]. Features [region]-style [instrument/technique]. Like [niche artist]'s work, capturing [specific mood].
```

## Systematic Prompt Refinement Methodology

### Cycle 1: Evaluate & Identify

1. **Generate your first track** using your initial prompt
2. **Score using the HARMONIC rubric**
3. **Identify the 2-3 lowest scoring categories**
4. **Analyze specific issues** within those categories:
   - Musical issues (rhythm, harmony, melody, structure)
   - Stylistic issues (genre authenticity, instrumentation)
   - Emotional issues (tone, impact, engagement)
   - Technical issues (production quality, artifacts)

### Cycle 2: Targeted Refinement

Choose refinement strategies based on your identified issues:

#### If Genre Authenticity is low:
- Add specific subgenre labels
- Reference influential artists in that genre
- Specify characteristic instruments or techniques
- Example: "Lo-fi hip-hop" → "Lo-fi hip-hop with jazz samples, boom-bap drums, vinyl crackle, inspired by J Dilla and Nujabes"

#### If Emotional Impact is low:
- Use stronger emotional language
- Specify dynamic changes (build-ups, drops)
- Connect emotions to specific musical elements
- Example: "Sad piano" → "Melancholic piano with gentle crescendos, emotional string swells, and moments of hopeful major chords"

#### If Structure/Coherence is low:
- Specify song structure explicitly
- Request clear transitions
- Define section lengths
- Example: "Pop song" → "Pop song with 16-bar verse, pre-chorus build-up, and catchy 8-bar chorus. Clear transition between sections."

#### If Production Quality is low:
- Specify mixing characteristics
- Request particular effects or processing
- Mention sound clarity
- Example: "Rock track" → "Polished rock track with clear separation between instruments, moderate reverb, and balanced mix"

### Cycle 3+: Fine-tuning & Steering

For subsequent iterations, use these steering techniques:

1. **Add/remove elements** with "more" or "less":
   - "More pronounced bass line"
   - "Less aggressive drums"

2. **Use contrast pairs** to clarify intent:
   - "Energetic but not chaotic"
   - "Melancholic without being depressing"

3. **Specify technical corrections**:
   - "Fix timing issues in the percussion"
   - "Create smoother transitions between verse and chorus"

4. **Incorporate successful elements**:
   - "Keep the melodic hook from the previous version"
   - "Maintain the atmospheric intro but develop it further"

## Adaptation Strategies for Different Backgrounds

### For International Students
- Use universal musical terms (fast/slow, happy/sad)
- Reference globally known artists when possible
- Describe the emotional journey rather than using idioms
- When targeting cultural music, use specific regional terms

### For Non-Musicians
- Focus on feelings and scenes: "Music that feels like walking through a forest at dawn"
- Reference media: "Like the soundtrack from [movie/game]"
- Describe activities: "Music for studying that helps concentration"
- Use metaphors: "Bright like sunshine" or "Heavy like storm clouds"

### For Technical Musicians
- Use music theory terms: "Dorian mode with modal interchange"
- Specify exact tempos: "72 BPM with swing feel"
- Name production techniques: "Side-chain compression on the bass"
- Reference specific playing techniques: "Fingerpicking acoustic guitar with hammer-ons"

## Troubleshooting Common Issues

### If AI misinterprets genre:
- Add 2-3 artist references that exemplify the genre
- Specify era (e.g., "early 90s hip-hop" not just "hip-hop")
- Include characteristic instruments or production techniques

### If emotional tone is wrong:
- Connect emotions to specific musical elements
- Use contrasting pairs to clarify boundaries
- Specify dynamic progression

### If quality is inconsistent:
- Request "professional production quality"
- Specify "coherent structure throughout"
- Ask for "well-balanced mix with clarity"

### If output is too generic:
- Add unique constraints or unusual combinations
- Request specific signature elements
- Incorporate niche references or techniques

Remember: The key to successful refinement is systematic, targeted changes based on your evaluation, not random adjustments. Document each change and its impact to develop your personal prompt engineering expertise.