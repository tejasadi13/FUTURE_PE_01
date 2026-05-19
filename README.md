# FUTURE_PE_01 - AI Website Copy Generator for Local Businesses

Future Interns Prompt Engineering Task 1, 2026

## Business Chosen

**ElevateIQ Academy, Hyderabad, Telangana**

Business type: Local coaching and test preparation academy  
Target audience: JEE, NEET, UPSC, and CAT aspirants, parents, and working professionals  
Tone: Professional, confident, supportive, and motivating  

## Project Goal

This project designs a reusable prompt framework that generates conversion-focused website copy for local businesses. The prompts are structured so they can be reused for salons, cafes, clinics, coaching centers, agencies, and freelancers by changing the business profile inputs.

For this task, the prompts are applied to ElevateIQ Academy to produce:

- Homepage copy with a clear value proposition
- Course and services page content
- CTA sections
- Tone-adapted website copy suitable for a real business website
- A static website preview created from the generated copy and Lovable-style website prompt

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
   - Encourage demo class bookings
   - Increase course inquiries
   - Improve trust
   - Make website copy clear and action-oriented

3. **Page-specific structure**
   - Homepage prompt creates the first impression
   - Services prompt explains courses clearly
   - CTA prompt turns visitor interest into action
   - Lovable website prompt turns the copy into a visual website preview

4. **Tone control**
   - Friendly for cafes and salons
   - Professional for clinics and agencies
   - Supportive and clear for coaching centers
   - Simple, confident, and human across all outputs

## Tool Used

Tools used: ChatGPT, Claude AI, Lovable-style website prompt

ChatGPT was used to structure the prompt framework and documentation. Claude AI was used to generate the website preview from the Lovable-style prompt. The final repository documents the complete workflow from prompts to outputs to visual website preview.

## Repository Structure

```text
FUTURE_PE_01/
|-- README.md
|-- business-profile.md
|-- prompts/
|   |-- master-prompt.md
|   |-- homepage-prompt.md
|   |-- services-prompt.md
|   |-- cta-prompt.md
|   `-- lovable-website-prompt.md
|-- outputs/
|   |-- homepage-copy.md
|   |-- services-copy.md
|   `-- cta-sections.md
`-- website-preview/
    `-- index.html
```

## Website Preview

A static website preview is included in `website-preview/`. It turns the generated homepage, course, and CTA copy into a professional coaching academy landing page so the final output can be reviewed visually.

To open it locally:

1. Open the `website-preview` folder.
2. Double-click `index.html`.

This preview is included to make the prompt engineering output easier to understand and present. The main task deliverables remain the structured prompts, generated outputs, and prompt logic documentation.

## Website Tool Prompt

The `prompts/lovable-website-prompt.md` file contains the website-generation prompt used to turn the copy direction into a visual landing page. This shows the full workflow from prompt design to generated copy to website preview.

## How To Reuse This Prompt System

1. Open `business-profile.md`.
2. Replace the academy details with a new local business.
3. Run the master prompt first to define the strategy.
4. Run the homepage, services, and CTA prompts.
5. Review the output for accuracy before publishing.

## Final Output Summary

The generated website copy positions ElevateIQ Academy as a focused coaching academy in Hyderabad for JEE, NEET, UPSC, CAT, and crash-course aspirants. The copy avoids unrealistic guarantees and focuses on small batches, expert guidance, mock-test practice, mentorship, and clear action steps such as booking a demo class.
