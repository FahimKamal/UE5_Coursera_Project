# Versatile Action-Adventure Character & Level Template

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.3.2+-blueviolet)](https://www.unrealengine.com/)
[![Focus](https://img.shields.io/badge/Focus-Character%20Animation%20&%20World%20Building-lightgrey)](https://www.google.com/search?q=character+animation+for+games)
[![Design Type](https://img.shields.io/badge/Design%20Type-Third--Person%20Action--Adventure%20Template-orange)](https://en.wikipedia.org/wiki/Action-adventure_game)
[![Coursera Certificate](https://img.shields.io/badge/Coursera-Visual%20Dev%20&%20Audio%20Design%20(Certified)-0056D2?logo=coursera)](https://www.coursera.org/learn/game-visual-development-and-audio-design?specialization=epic-games-game-design-professional-certificate)
[![Status](https://img.shields.io/badge/Status-Project%20Complete%20&%20Certified-success)](./)

---

<!--
======================================================================
=== VISUAL SHOWCASE (MAIN VIDEO & HERO IMAGE) ===
======================================================================
-->

<p align="center">
  <!-- 🛑 ACTION REQUIRED: Replace this image source with a hero shot of your redesigned level -->
  <img src="https://via.placeholder.com/1200x675.png?text=PLACEHOLDER:+Your+Redesigned+Level+Hero+Image" alt="Hero Image of the Redesigned Egypt Level" width="80%"/>
  <br>
  <em>A representative hero image of the completed "Sanctuary of Whispering Sands" level template.</em>
</p>

---

## 🎓 Project Context & Motivation

This project was developed by **Fahim Kamal Ahmed** as the successfully completed capstone assignment for the **[Visual Development and Audio Design in Games](https://www.coursera.org/learn/game-visual-development-and-audio-design?specialization=epic-games-game-design-professional-certificate)** course. This is the fifth course in the **[Epic Games Game Design Professional Certificate](https://www.coursera.org/professional-certificates/epic-games-game-design-professional-certificate#courses)** offered on Coursera.

The development focused on creating a feature-rich, versatile character and a multi-purpose level template. Starting with a basic third-person character, the project involved implementing a complex animation system from the ground up, building a dynamic weapon-swapping framework, and integrating a host of visual effects and audio systems to create a polished, "game-feel" ready foundation for future development.

---

## 🎯 Overview

This project is a comprehensive and versatile **Third-Person Action-Adventure Template** built in **Unreal Engine 5**. It features a highly capable character with a full suite of mobility options and a dynamic animation stance system that supports multiple weapon types.

The core of the project is a fully redesigned level, transformed from the "Stylized Egypt" pack into a multi-purpose template environment. This template is designed to be the foundational starting point for six distinct game modes—ranging from Stealth Survival to Action Combat—that will be built in the final capstone course of the professional certificate.

---

## 🗺️ Project Brief & Design Goals

The primary goal was to take the "Stylized Egypt" level and redesign it into a single, cohesive, and multi-purpose template that could realistically serve as the setting for six different game genres. This involved not just re-decorating, but fundamentally rethinking the level's flow and layout to accommodate various gameplay needs.

The complete design philosophy, a breakdown of the level redesign, and the detailed intentions for accommodating future game modes are documented in the Project Design Document.

<p align="center">
  <!-- 🛑 ACTION REQUIRED: Upload your project PDF to your repository and change this file name -->
  <a href="The Sanctuary of Whispering Sands.pdf" target="_blank"> 
    <strong>View the Full Project Design Document (PDF)</strong>
  </a>
</p>


---

## ✨ Key Goals & Features (Achieved in Project)

*   **Dynamic Animation Stance System:** Architected a robust, enumeration-driven system allowing the character to seamlessly switch between **6 distinct animation stances** (Unarmed, Shield, Two-Handed, Rifle, Bow, Stealth), each with unique idle and locomotion animations.
*   **Layered Upper-Body Animation:** Implemented a **`Layered blend per bone`** system that allows the character to perform upper-body actions (like attacking) while the lower body continues its locomotion cycle, preventing "ice skating" and dramatically improving game feel.
*   **Full Suite of Mobility Mechanics:** The character controller was expanded with a complete mobility kit, including a directional **Dodge Roll**, an **Air Dash**, and a **Double Jump**.
*   **Dynamic Weapon Swapping Framework:** Created a centralized function to dynamically attach, detach, and manage the visibility of multiple weapon components based on the character's current animation stance. This includes handling `SkeletalMesh` and `StaticMesh` components attached to multiple custom sockets.
*   **Resourceful 3D Implementation:** Demonstrated creative problem-solving by repurposing assets for new roles, such as using a decorative ornament as a functional shield and a two-handed axe as a placeholder bow.
*   **In-Engine 3D Modeling:** Modeled and textured a custom 3D asset (the "Baked Bun" sign) from scratch using Unreal Engine's built-in **Modeling Tools** and applied it to the world using a custom **Decal Material**.
*   **Dynamic Audio Systems:**
    *   Implemented randomized footstep and attack sounds to avoid repetition and enhance immersion.
    *   Created a dynamic, trigger-based music system that fades between different audio tracks as the player moves between zones.
*   **VFX & Niagara Implementation:** Gained a foundational understanding of the Niagara VFX system, creating custom emitters and systems and learning to trigger them via Blueprints and Animation Notifies.

---

## 📜 Certificate of Completion - Visual Development and Audio Design in Games

I am proud to have successfully completed this course and earned my certificate!

<p align="center">
  <!-- 🛑 ACTION REQUIRED: Replace this image with your actual certificate screenshot -->
  <img src="https://via.placeholder.com/1200x800.png?text=PLACEHOLDER:+Your+Course+5+Certificate" alt="Certificate for Visual Development and Audio Design in Games" width="70%"/>
  <br>
  <em>Certificate of Completion - Visual Development and Audio Design in Games.</em>
  <br>
  <!-- 🛑 ACTION REQUIRED: Replace this link with your certificate verification link -->
  <a href="https://www.coursera.org/account/accomplishments" target="_blank">
    <strong>Verify Certificate</strong>
  </a>
</p>

---

## 📸 Development Screenshots (Completed Project)

<p align="center">
  <!-- 🛑 ACTION REQUIRED: Add screenshots showcasing your work. Examples below. -->
  <img src="https://via.placeholder.com/1200x675.png?text=PLACEHOLDER:+Screenshot+of+your+Bakery" alt="Bakery Screenshot" width="80%"/>
  <br/>
  <img src="https://via.placeholder.com/800x450.png?text=PLACEHOLDER:+Shield+Stance" alt="Shield Stance Screenshot" width="45%"/>
  <img src="https://via.placeholder.com/800x450.png?text=PLACEHOLDER:+Rifle+Stance" width="45%"/>
  <br/>
  <img src="https://via.placeholder.com/800x450.png?text=PLACEHOLDER:+Air+Dash+in+action" alt="Air Dash Screenshot" width="45%"/>
  <img src="https://via.placeholder.com/800x450.png?text=PLACEHOLDER:+VFX+Example" alt="VFX Screenshot" width="45%"/>
  <br/>
</p>

---

## 💻 Technology Stack

*   **Engine:** Unreal Engine 5.3.2+ ⚙️
*   **Core Packages Utilized:**
    *   **Unreal Engine Third-Person Template:** Used as the base for player character and movement.
    *   **Stylized Egypt:** Primary environment asset pack.
    *   **Infinity Blade: Weapons:** Used for all melee weapons and the placeholder "bow".
    *   **FANTASTIC Village Pack, Advanced Village Pack, Lowpoly Handpainted Environment:** Used for environment redesign.
    *   **Cropout & Stack O Bot Samples:** Used for migrating additional VFX and SFX assets.
*   **Unreal Engine Features Used:**
    *   Animation Blueprints (Event Graph & Anim Graph)
    *   **Animation Blend Spaces**, **Animation Montages**
    *   **`Layered blend per bone`** and Custom Animation Notifies
    *   Blueprint Interfaces & Enumerations
    *   **Sockets** for Skeletal Mesh attachments
    *   **In-Engine Modeling Tools** & Decal Actors
    *   **Niagara** VFX System (Emitters & Systems)
    *   Dynamic Audio (Player Controller Audio Component, Sound Cues, `Play Sound at Location`)
    *   Enhanced Input System (Input Actions & Mapping Contexts)
*   **External Tools:**
    *   **Mixamo:** Sourced all character animations.
*   **Course:** [Visual Development and Audio Design in Games](https://www.coursera.org/learn/game-visual-development-and-audio-design?specialization=epic-games-game-design-professional-certificate) (Epic Games / Coursera)

---

## 🔮 Future Plans (Next Steps in Course 8)

This project serves as the direct foundation for the final capstone, **Course 8: Game Development and Prototyping.** The plan is to duplicate this entire template level six times, with each copy being uniquely modified to fit one of the following game modes:

*   🤖 **Stealth Survival:** Emphasize the level's shadows and cover, populating it with enemy patrols.
*   🧗 **Platformer:** Build upon the vertical elements, adding moving platforms and collectibles.
*   🚩 **Capture the Flag:** Design two distinct bases within the level and implement flag-capture logic.
*   ⚔️ **Action Combat:** Populate the designated combat arenas with enemies and a final boss.
*   🛠️ **Crafting:** Implement resource nodes at the oasis and add building mechanics.
*   📜 **Story:** Add quest-giving NPCs, interactive items, and puzzles.

---

## 📜 Assets & Attributions

*   **Course:** This project is an assignment for the **[Visual Development and Audio Design in Games](https://www.coursera.org/learn/game-visual-development-and-audio-design?specialization=epic-games-game-design-professional-certificate)** course by Epic Games on Coursera.
*   **Creator (System Design, Level Redesign, Blueprinting):** Fahim Kamal Ahmed
*   **Character Animations:** All character animations were sourced from **Adobe Mixamo**.
*   **Third-Party Assets:**
    *   This project utilizes several free and sample asset packs from the Unreal Engine Marketplace, including `Stylized Egypt`, `Infinity Blade: Weapons`, `FANTASTIC Village Pack`, and assets migrated from the `Cropout` and `Stack O Bot` samples. All rights belong to their respective creators.
    *   The project was built upon the standard **Unreal Engine Third-Person Template**.

---

## ⚖️ Licensing

This project by **Fahim Kamal Ahmed** is licensed under the **MIT License**. Please see the `LICENSE` file for full details. Note that third-party assets are subject to their own licenses.