# Vo-Gems Technical Specifications

## Project Overview

**Vo-Gems** is a platform designed to bring authenticity back to music and give artists a safe, human-feeling space to reclaim their own voice. The platform must feel like an extension of the Vo-Gems companion website — warm, welcoming, and built entirely around creator empowerment and artistic authenticity.

**Current Status:** Live in Google AI Studio sandbox (development mode). All core features and functionality are operational. The primary challenge is aligning the visual design, aesthetics, and user interface with the established design vision.

---

## Design Requirements

### Core Design Philosophy

The Vo-Gems build must embody:
- **Warmth and authenticity** over corporate sterility
- **Artist empowerment** over surveillance or monitoring
- **Simplicity and clarity** over technical complexity
- **Human connection** over mechanical automation
- **Safety and trust** over data extraction

The entire platform must feel like it comes from the same soul as the companion website.

---

## Visual Design Specifications

### Color Palette

The following colors must be used consistently throughout the entire platform:

| Color | Hex Code | Usage |
|-------|----------|-------|
| Teal | `#20B2AA` or `#008B8B` | Primary background, accents, trusted elements |
| Neon Pink | `#FF1493` or `#FF69B4` | Highlights, call-to-action elements, energy points |
| Gold | `#FFD700` or `#FFA500` | Accent color, emphasis on key words, premium feel |
| Burgundy | `#800020` or `#8B0000` | Deep accents, secondary highlights |
| Deep Purple | `#2C0845` or `#4B0082` | Tertiary accents, sophisticated elements |

**Avoid:**
- Bright cyan/neon blue (corporate tech feel)
- High-contrast black and white (harsh, surveillance-like)
- Grays that feel cold or sterile

---

### Typography

**Font Requirements:**
- **Primary Font:** Warm, readable, human-feeling serif or sans-serif (e.g., Inter, Montserrat, Open Sans, Georgia)
  - NO computerized or monospace fonts
  - NO technical/robotic typefaces
  - Should match the companion website's typography

- **Heading Font:** Clear, inviting, authentic (complements primary)
  - Warm personality
  - Easy to read
  - Never intimidating or mechanical

- **Body Text Font:** High readability, human warmth
  - Size: Minimum 14px on desktop, 12px on mobile
  - Line height: 1.6 or greater for comfortable reading
  - Color: Dark on light, or light on dark (never harsh contrast)

**Avoid:**
- Courier, Consolas, or other monospace fonts
- Overly stylized or decorative fonts that reduce readability
- Fonts that feel robotic, corporate, or technical

---

### Layout & Interface Design

#### General Principles
- **Scrollable, simple layout:** Primary action should be accessible without overwhelming the user
- **Clean spacing:** No clutter, no crowded elements
- **Intuitive navigation:** Essential features (export, share, claim-your-voice) must be logically ordered and easy to find
- **Mobile-responsive:** Works seamlessly on all device sizes
- **Warm, welcoming aesthetics:** Calm and inviting, never harsh or intimidating

#### Specific Interface Elements

**Buttons & Call-to-Action:**
- Primary CTA buttons: Neon pink or gold background
- Secondary buttons: Teal or burgundy
- Hover states: Slightly darker shade, smooth transition
- Text: Clear, human language (e.g., "Claim Your Voice" not "Authorize Access")

**Navigation:**
- Menu structure: Simple, hierarchical
- Labels: Warm, everyday language
- Icons: Simple, friendly (not technical symbols)
- No "hamburger" menus unless necessary (prefer visible navigation)

**Visual Feedback:**
- **NO blinking lights** (creates surveillance feel)
- **NO harsh loading indicators** with technical symbols
- Soft transitions and animations
- Minimal, calming visual cues

**Content Areas:**
- Generous padding and margins
- Text contrast that's readable but not harsh
- Soft backgrounds (never pure white if possible)
- Visual hierarchy that guides the eye naturally

---

## Language & Messaging Requirements

### Human-First Language Standards

**Every word must:**
- Use everyday vocabulary
- Be warm and inviting
- Avoid technical jargon
- Never create fear or uncertainty
- Empower the artist, not the platform

**Examples of what to use:**
- "Claim Your Voice" instead of "Authenticate"
- "Share Your Song" instead of "Export Data"
- "Your Music, Your Rules" instead of "Access Control"
- "Tell Your Story" instead of "Input Metadata"

**Examples of what to NEVER use:**
- "Sovereign" (forbidden)
- "Pedigree" (forbidden)
- "Authenticate," "authorize," "mandate"
- "AI," "algorithm," "processing," "synthesize" (unless necessary for clarity)
- "Data collection," "tracking," "monitoring," "analysis"
- "Metadata," "parameters," "leverage," "optimize"
- "TTS," "Gemma," "co-pilot," or other technical acronyms
- Any language that implies surveillance or data extraction

### Messaging Framework

#### Welcome/Homepage
**Tone:** Warm, inviting, welcoming
- Greet the artist as a peer, not a user
- Emphasize the mission: bringing authentic voices back to music
- Create a sense of safety and belonging
- Make the purpose clear: "This is built by artists, for artists"

**Example messaging:**
- "Welcome to Vo-Gems — Where your music stays yours."
- "Your voice matters. Your story matters. Your music is yours to share."

#### Feature Descriptions
**Tone:** Clear, simple, empowering
- Explain what each feature does in plain language
- Focus on artist benefit, not platform capability
- Never imply hidden data usage or monitoring

**Example:**
- Instead of: "Leverage AI-driven vocal replacement synthesis"
- Use: "Add beautiful harmonies to your vocals"

#### Error Messages
**Tone:** Supportive, helpful, human
- Never technical or blaming
- Offer clear next steps
- Reassure the artist that the platform is working for them

**Example:**
- Instead of: "Error 500: Server processing failed"
- Use: "We had a hiccup. Try again in a moment, or reach out if this keeps happening."

---

## Feature Specifications

### Core Features (Priority Order)

1. **Claim Your Voice**
   - Simple, one-step interface
   - Clear explanation of what claiming means
   - Warm confirmation and celebration when complete

2. **Create/Compose**
   - Intuitive interface for song creation
   - Clear, labeled sections
   - Easy access to tools without overwhelming options

3. **Share Your Song**
   - Simple sharing options (email, social, direct link)
   - Warm messaging about sharing
   - Clear ownership statement with each share

4. **Listen & Refine**
   - Easy playback controls
   - Clear comparison options
   - Simple adjustment tools
   - Intuitive feedback mechanism

5. **Export Your Music**
   - Multiple format options, clearly labeled
   - Simple one-click export
   - Confirmation that the music is theirs to keep

### Feature Layout

**Requirements:**
- All essential features must be accessible from the main view (scrollable)
- No buried menus or hidden functionality
- Clear, logical grouping of related features
- Visual hierarchy that guides the artist to their most common actions

---

## Creator Safety Standards

### What the Interface Must Never Do

1. ❌ Imply data collection or surveillance
   - No language about "analyzing" or "tracking"
   - No privacy disclaimers that sound like data harvesting
   - No hidden telemetry or behavioral tracking UI

2. ❌ Create fear or uncertainty
   - No warning dialogs
   - No technical error messages
   - No language suggesting the artist is giving up rights

3. ❌ Suggest the platform is replacing the artist
   - Clear messaging: "Tools to enhance, not replace"
   - Emphasis on artist control and creative direction
   - Regular affirmation of ownership

4. ❌ Use corporate or corporate-feeling language
   - No "terms and conditions" vibes
   - No legal jargon in the main interface
   - No language that feels like a corporation talking down to users

### What the Interface Must Do

1. ✅ Affirm artist ownership constantly
   - "Your music, your rules"
   - Clear statements of who owns the final work
   - Easy access to proofs of ownership

2. ✅ Be transparent about the platform's purpose
   - Clear explanation: "Built by an artist, for artists"
   - Simple statement of mission
   - Easy access to the founder's story

3. ✅ Offer simple, direct support
   - Human contact options (not just chatbots)
   - Clear, simple FAQ
   - Warm tone in all help content

4. ✅ Make it easy to access/control your data
   - Clear, simple data download option
   - Easy deletion option if artist wants to leave
   - No data lock-in or hidden requirements

---

## Aesthetic Guidelines

### Visual Feel

**Should evoke:**
- Creativity and artistic expression
- Safety and belonging
- Authenticity and realness
- Energy and movement
- Professional quality

**Should NOT evoke:**
- Corporate surveillance
- Technical complexity
- Corporate sterility
- Monitoring or tracking
- Intimidation or fear

### Design References

The Vo-Gems build should feel like a natural extension of:
1. **The Vo-Gems companion website** (warm, scrollable, calm)
2. **Modern creative tools** (Canva, Adobe Express) but warmer
3. **Artist community platforms** (SoundCloud, Bandcamp) but more human
4. **Not like:** Technical platforms (GitHub, AWS), Corporate software, Surveillance tools

### Animation & Interaction

**Should:**
- Use smooth, gentle transitions
- Provide clear visual feedback on interactions
- Celebrate artist actions (positive reinforcement)
- Animate with purpose, not distraction

**Should NOT:**
- Use blinking or flashing effects
- Create a "loading" or "processing" feel
- Use harsh or jarring animations
- Distract from the artist's creative work

---

## Technical Implementation Notes

### Current Challenge

The Vo-Gems build is currently hosted in **Google AI Studio** with all core functionality working correctly. However, Google AI Studio's default interface design cannot be fully customized through text-based instructions alone. The UI remains corporate/technical, and the color palette cannot be changed from the platform's defaults.

### Recommended Solutions

#### Solution 1: Custom Frontend Wrapper (Recommended for Short-term)
- Keep Google AI Studio backend for AI functionality
- Build a custom HTML/CSS/JavaScript frontend
- This frontend would:
  - Display the Vo-Gems color palette and typography
  - Provide warm, human-centered messaging
  - Wrap the Google AI Studio API calls
  - Create the scrollable, simple layout
- **Advantage:** Fastest to implement, keeps working backend
- **Effort:** Moderate (4-6 weeks for experienced developer)

#### Solution 2: Migration to Custom Platform (Better for Long-term)
- Move to **GitHub Codespaces** or **Replit** with a full custom build
- Use Google's Generative AI API directly (not through Studio)
- Build entire frontend and backend with full control
- **Advantage:** Complete control, fully branded, scalable
- **Effort:** Significant (2-3 months for full build)

#### Solution 3: Hybrid Approach
- Keep Google AI Studio for quick prototyping
- Build custom platform in parallel
- Transition users to custom platform when ready
- **Advantage:** No downtime, maintains functionality while improving UX

---

## Success Criteria

The Vo-Gems build will be considered complete when:

✅ **Visual Design**
- All five brand colors appear consistently throughout
- Typography is warm, readable, human-feeling
- No harsh contrasts or corporate aesthetics
- Layout is scrollable and simple

✅ **Language & Messaging**
- Zero technical jargon in user-facing text
- All messages are warm, clear, and artist-empowering
- Words "sovereign" and "pedigree" never appear
- Every button and feature uses human-first language

✅ **User Experience**
- Artist can navigate all core features without confusion
- All essential actions are 2-3 clicks maximum
- Interface feels safe, not like surveillance or monitoring
- No blinking lights, harsh UI elements, or intimidating language

✅ **Emotional Resonance**
- Artists feel welcomed and empowered
- Interface feels like an extension of the companion site
- Platform feels built by an artist, for artists
- Overall emotional temperature matches the mission

✅ **Functionality**
- All core features work as designed
- No broken links or missing functionality
- Export, share, and claim-your-voice are easily accessible
- Platform remains accessible and fast

---

## Next Steps for Implementation

1. **Document Approved:** Share this specification document with development team
2. **Design Mockups:** Create visual mockups showing current vs. desired state
3. **Platform Decision:** Choose between custom frontend wrapper or full migration
4. **Development:** Implement design specifications
5. **Testing:** Verify all requirements met before launch
6. **Iteration:** Gather artist feedback and refine

---

## Questions & Support

If you have questions about these specifications:
- What's unclear?
- What needs more detail?
- What constraints are you facing?

This document should serve as the north star for all design and development decisions going forward.

---

**Document Version:** 1.0  
**Last Updated:** May 27, 2026  
**Status:** Ready for Implementation
