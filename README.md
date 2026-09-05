# My-projects
LED Chaser Circuit — Circuit Design & Construction

EENG 1910, University of North Texas

I designed, built, and tested a 10-LED chaser circuit that uses an NE555 timer in astable mode to generate a clock signal that drives a CD4017 decade counter to sequentially light 10 LEDs, creating a smooth "chasing" light effect whose speed is adjustable via a potentiometer. Before soldering, I modeled and validated the design in Multisim, which let me confirm the timing behavior and current-limiting resistor values before the physical build. I also worked through the underlying math: applying Ohm's Law to size the current-limiting resistors (verifying roughly 4 mA per LED at 6V) and using the 555 timer's frequency equation to understand how resistor and capacitor values set the chase speed.

The build wasn't perfect on the first try — and that's part of what made it a good learning experience. Across three assembly attempts, I diagnosed and fixed reversed component polarity on LEDs, capacitors, and ICs, solder bridges that created unintended current paths, and loose connections causing intermittent behavior. Each failure narrowed down to a specific, testable cause, and the final board ran cleanly: all ten LEDs illuminated in a consistent, repeating sequence.

What this demonstrates: systematic debugging, careful reading of circuit diagrams, understanding of timing and sequential logic circuits, and the discipline to verify a design in simulation before committing it to hardware.

Built with Aron Hernandez and Cameron Halsell.

Teletutor — Academic Support Platform (Concept & Front-End Prototype)

CSCE 1015, "Time Machine" team

Teletutor is a multi-page web platform concept aimed at closing the gap between when students get stuck on schoolwork and when help is actually available. I worked with my team to design a tiered support model — a free peer Q&A community, scheduled sessions with a trusted tutor, and an on-demand premium tier — and to build out a front-end prototype demonstrating how each type of user (student, tutor, parent/guardian, and admin) would move through the platform. My contributions included designing the Q&A submission-and-answer flow and dashboard views that let students track progress and let tutors manage sessions and availability.

As a team, we followed a real development workflow: feature branches, pull requests before merging, consistent file naming, and documented meeting decisions — practices that mirror how software teams collaborate in industry.

What this demonstrates: UX thinking for multiple user roles, translating a product pitch into a structured site architecture, and collaborative software development practices (Git branching, PR review, team documentation).

Built with Leticia Bromley, Lexie Dallison, Aron Hernandez, and Pooja Lamsal.

Time Machine Recipe Book — Team Website

HTML & CSS

A collaborative recipe-sharing website built from the ground up with semantic HTML and a custom external CSS stylesheet. The site includes a header, a team introduction section with linked profile photos, and a recipe gallery — with each recipe opening on its own page complete with an ingredient list, step-by-step instructions, and a link back to the main gallery. I focused on the visual design system: flexbox layouts for a clean, responsive structure, hover effects and transitions, and rounded images with subtle shadows to give the site a polished, cohesive feel.

What this demonstrates: semantic HTML structure, CSS layout techniques (flexbox, responsive design), and attention to consistent, user-friendly visual design.

Built with Leticia Bromley, Lexie Dallison, Aron Hernandez, and Pooja Lamsal.
Self-Sustaining Renewable Energy House Circuit — Final Project Proposal

EENG 1910, University of North Texas

For my final project, my team and I proposed a small-scale circuit that models how a home could run on renewable energy. The design combines two independent generation sources — a DC motor acting as a wind-turbine generator and a solar cell — each feeding its own storage stage (batteries or capacitors) before passing through a regulated circuit to power a set of LEDs representing rooms in a house. Switches let us manually select which energy source powers the "house" at any given time, and diodes, a voltage regulator, and current-limiting resistors protect the circuit and keep the output steady. I led the project planning: building out the timeline (Gantt chart and network diagram), organizing the team's workflow, and preparing the final presentation materials, while collaborating with my teammates on sourcing parts, soldering, testing, and troubleshooting the build.

What this demonstrates: systems-level circuit design combining multiple energy sources, project planning and scheduling for a multi-week technical build, and budgeting/feasibility analysis alongside the engineering itself.

Proposed and built with Aron Hernandez and Cameron Halsell.
