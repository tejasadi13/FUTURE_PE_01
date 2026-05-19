# FUTURE_PE_01 - AI Website Copy Generator for Local Businesses

Future Interns Prompt Engineering Task 1, 2026

## Business Chosen

**BrightPath Coaching Centre, Indiranagar, Bangalore**

Business type: Local coaching and test preparation center  
Target audience: Students, exam aspirants, and parents looking for structured academic support  
Tone: Professional, supportive, clear, and encouraging  

## Project Goal

This project designs a reusable prompt framework that generates conversion-focused website copy for local businesses. The prompts are structured so they can be reused for salons, cafes, clinics, coaching centers, agencies, and freelancers by changing the business profile inputs.

For this task, the prompts are applied to BrightPath Coaching Centre to produce:

- Homepage copy with a clear value proposition
- Services page content
- CTA sections
- Tone-adapted website copy suitable for a real business website
- A static website preview showing how the generated copy can look on a real website

## Prompt Logic

The prompt framework uses four layers:

1. **Business context**
   - Business name
   - Location
   - Audience
   - Services
   - Brand personality
   - Customer pain points

2. **Conversion goal**
   - Encourage class inquiries
   - Increase inquiries
   - Improve trust
   - Make website copy clear and action-oriented

3. **Page-specific structure**
   - Homepage prompt creates the first impression
   - Services prompt explains offerings clearly
   - CTA prompt turns visitor interest into action

4. **Tone control**
   - Friendly for cafes and salons
   - Professional for clinics and agencies
   - Supportive and clear for coaching centers
   - Simple, confident, and human across all outputs

## Tool Used

Tool used: ChatGPT

ChatGPT was used to design the prompt framework and generate the final website copy outputs from the selected business profile.

## Repository Structure

```text
FUTURE_PE_01/
|-- README.md
|-- business-profile.md
|-- prompts/
|   |-- master-prompt.md
|   |-- homepage-prompt.md
|   |-- services-prompt.md
|   `-- cta-prompt.md
|-- outputs/
|   |-- homepage-copy.md
|   |-- services-copy.md
|   `-- cta-sections.md
`-- website-preview/
    |-- index.html
    `-- styles.css
```

## Website Preview

A static website preview is included in `website-preview/`. It turns the generated homepage, services, and CTA copy into a simple coaching center landing page so the final output can be reviewed visually.

To open it locally:

1. Open the `website-preview` folder.
2. Double-click `index.html`.

This preview is included to make the prompt engineering output easier to understand and present. The main task deliverables remain the structured prompts, generated outputs, and prompt logic documentation.

## How To Reuse This Prompt System

1. Open `business-profile.md`.
2. Replace the coaching center details with a new local business.
3. Run the master prompt first to define the strategy.
4. Run the homepage, services, and CTA prompts.
5. Review the output for accuracy before publishing.

## Final Output Summary

The generated website copy positions BrightPath Coaching Centre as a reliable academic support center in Indiranagar where students can build stronger concepts, better study habits, and exam confidence. The copy avoids fake guarantees and focuses on clarity, parent trust, student motivation, and action-oriented website messaging.
