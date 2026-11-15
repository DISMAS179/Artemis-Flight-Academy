<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Artemis Flight Academy
A kid-friendly NASA astronaut training game for ages 7 to 12
A browser-based astronaut training game inspired by NASA missions. Players dock a spacecraft, run a Moon or Mars base, handle emergencies and earn badges.
# Try the app: [https://dismas179.github.io/Artemis-Flight-Academy/]
# 1. Project Title
Artemis Flight Academy
# 2. What We Developed
A full-stack space training game with five parts:

  •Space Docking: a 3D spacecraft docking game with realistic motion (6 directions of movement, fuel use, autopilot), VR support and multiplayer rooms.
  
  •Moon & Mars Base: an outpost game where players share limited power between air, radiation shielding, food and water.
  
  •Mission Control: a live console where an instructor watches trainees and sends radio messages or practice emergencies.
  
  •AI Flight Coach: feedback on what the cadet did well and what to practise, plus a skills chart.
  
  •Safety Vault: badges, an activity log and encrypted flight credentials.
  
# 3. How It Addresses the Challenge
It turns NASA-style training (docking, life support, emergency drills, teamwork with ground control) into a game that students can play in any browser. Players practise the same trade-offs real crews face, such as fuel versus speed and power versus safety, without needing expensive hardware.
# 4. Why It Is Important

•Astronaut training is costly and limited to a few people. A free game opens space careers to young learners.

•It builds STEM skills and safe decision-making under pressure.
•Instructors get cloud progress tracking and analytics instead of guessing where learners struggle.
•Audit logs and encryption show how a real training platform must handle safety and compliance.
# 5. How It Works

1.The player signs in with Google (Firebase) and picks a mission.

2.Docking: arrow keys or on-screen buttons fire thrusters. A physics engine updates speed, position, rotation and fuel. A dock counts as safe only if speed, alignment and angle are within NASA-style limits.

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

