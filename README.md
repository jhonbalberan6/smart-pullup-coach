# smart-pullup-coach
An autoregulating pull-ups workout tracker built with Human-Centered Design (HCD) principles to act as a supportive digital coach.

Smart Pull-Up Coach

A single-file, mobile-optimized web application that acts as an intelligent, autoregulating spotter for your pull-up workouts.

Instead of just tracking reps, this app uses a math-based engine to adjust your rest times and next-set targets based on your real-time fatigue and form degradation.

The Design Philosophy

Fitness apps often fall into the trap of looking like "crypto trading terminals"—dark, intimidating, and overly technical. When users are physically exhausted, they need an interface that reduces cognitive load, not one that adds to it.

This app was built from the ground up using Modern Human-Centered Design (HCD) principles:

Color Psychology: The UI uses a low eye-strain off-white background (#F3F4F6) instead of pure white or harsh black. The primary action color is Indigo (which promotes trust, calm, and focus) and Emerald Green (which promotes feelings of growth and health).

Soft Geometry & "Squicles": Sharp 90-degree corners subconsciously trigger a caution response. This app utilizes soft geometry, large border radii, and pill-shaped buttons to make the interface feel friendly, tactile, and safe.

Elevated Surfaces: To create visual hierarchy without harsh borders, content is grouped into pure white floating cards with soft, diffuse drop shadows.

Conversational Microcopy: Technical jargon like "RIR" (Reps in Reserve) or "Form Quality Matrices" has been translated into plain, conversational English (e.g., "Reps left in the tank"). The rest timer acts as a friendly chat bubble from a virtual coach rather than a clinical diagnostic readout.

How the Engine Works

The app calculates your rest time and next target based on three inputs:

Volume: How many reps you actually completed vs. your baseline.

Reps Left in Tank (RIR): Your perceived exertion.

Form Quality: A 1-5 scale of how strict the movement was.

If your form breaks down or your reps drop past a certain threshold based on your selected goal (Strength, Volume, or Recovery), the app will automatically terminate the workout to prevent injury and optimize recovery.

How to Run

Because this is built as a highly optimized, dependency-free single HTML file, you don't need to install anything.

Clone or download this repository.

Open index.html in any modern web browser.

(Optional) Save it to your iOS or Android home screen—it includes an embedded PWA manifest to act like a native app!

Tech Stack

HTML5

CSS3 (Custom UI properties + Bootstrap 5 layout utilities)

Vanilla JavaScript (ES6)
