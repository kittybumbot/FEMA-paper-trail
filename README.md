# Paper Trail: FEMA Cost Recovery

A game-show-style learning game for emergency managers and local government staff. Players work through disaster procurement decisions under changing conditions, then find out 18 months later, in a simulated FEMA closeout audit, how much federal reimbursement their decisions recovered.

**Play it:** open `index.html` in any modern browser. Nothing needs to be installed, and the game runs entirely in the browser.

## Learning objectives

Learners will be able to:

1. Describe the general procurement standards in Title 2, Part 200, Subpart D of the Code of Federal Regulations (2 CFR 200).
2. Given a scope of work, apply the Subpart D procurement standards and determine what documentation is required to support reimbursement eligibility from FEMA.

## Intended learners

Emergency managers and local government administrative staff who regularly take part in tabletop exercises, Golden Eagle simulations, and other preparedness training, and who need to apply federal procurement rules accurately before, during, and after disasters.

## How it works

1. **Check in.** The player is randomly assigned to an EOC section: Operations, Planning & Intelligence, Logistics, or Finance & Administration.
2. **Five scenarios, one at a time:** preparedness and mitigation purchasing, nuisance flooding, a debris flow, wildfire mass sheltering, and wildfire debris removal.
3. **Each scenario includes:**
   - the player's section call
   - a procurement method decision
   - two injects that change the conditions mid-scenario, each followed by a timed decision
   - building the procurement file
4. **The clock runs on each decision.** If it runs out, the decision is made by default, usually the knee-jerk shortcut. Players can choose Standard (25 seconds), Relaxed (60 seconds), or Untimed, and can pause at any time.
5. **No feedback during play.** After the last scenario, the game jumps 18 months ahead to a closeout audit. The audit shows the federal share recovered, rates each decision, lists file findings (missing documents, documents listed that didn't exist, and weak evidence), and checks how the player used the emergency exception.

## Design notes

- **The delayed feedback is deliberate.** It mirrors how consequences actually arrive in cost recovery work.
- **The documentation step rewards accuracy, not volume.** Listing a document that none of the player's decisions produced costs as much as leaving out a required one.
- **Injects nudge players away from the reflex to call everything an emergency.** Some injects reward changing course, and others reward holding steady.
- **Thresholds follow a sample local policy.** Micro-purchases run up to $10,000, and formal solicitation with Board approval applies above $200,000. Both are stricter than the federal limits effective October 1, 2025 ($15,000 and $350,000), so the local limits govern.

## Accessibility

- Adjustable or disabled timing, plus a pause control (WCAG 2.2.1).
- Full keyboard play: answer with A–D or 1–4.
- Visible focus states.
- Screen-reader announcements for injects, timers, and locked answers.
- Support for reduced-motion preferences.
- A layout that works from phone to desktop.

## Publishing with GitHub Pages

1. Add `index.html` and this README to your repository, either at the root or in a folder such as `/paper-trail`.
2. In the repository, go to **Settings → Pages** and set the source to your main branch.
3. The game will be available at `https://<username>.github.io/<repository>/`, with `/paper-trail/` added at the end if you used a folder.

## Disclaimer

This is a training simulation. Dollar figures, scoring, and audit outcomes are illustrative; FEMA reviews each project on its own facts. For current policy, check the FEMA Public Assistance Program and Policy Guide, FEMA's procurement guidance resources, and your Cal OES representative.

## Credits

Designed by Kathryn Hussein for M.S. Instructional Design and Technology coursework at San José State University. Developed in collaboration with Claude (Anthropic) as a generative AI development partner.
