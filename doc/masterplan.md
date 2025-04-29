# **Masterplan.md – AI Learning Blueprint Platform**

## **1\. App Overview and Objectives**

The AI Learning Blueprint Platform is a web-based application designed to help founders and beginner developers—regardless of coding experience—create personalized, structured learning plans for mastering artificial intelligence. Through a guided onboarding process and OpenAI-powered blueprint generation, the platform delivers curated educational paths tailored to the user’s goals, background, and time commitment. It also enables bookmarking of high-quality AI resources and supports multiple learning tracks per user.

## **2\. Target Audience**

* **Primary Users:**  
  * Non-technical startup founders wanting to build AI products  
  * Beginner developers transitioning into AI development  
* **Secondary (future) Users:**  
  * Creatives, writers, and marketers exploring AI tools  
  * Intermediate and advanced developers seeking specialized tracks

## **3\. Core Features and Functionality**

* Guided onboarding survey to define goals and experience  
* OpenAI-powered blueprint generation based on user input  
* Support for multiple blueprints per user  
* Resource bookmarking and library management  
* Searchable curated database of AI courses, tools, and tutorials  
* Stripe integration for paid subscriptions (Pro plan)  
* Future integrations: Google Drive (export), email onboarding, YouTube API, community features

## **4\. Technical Stack (High-Level)**

* **Frontend:** Lovable (no-code/low-code platform)  
* **Backend:** Supabase (PostgreSQL, Auth, Storage, Functions)  
* **Hosting/CI:** Vercel \+ GitHub  
* **AI Services:** OpenAI API  
* **Payments:** Stripe Checkout & Webhooks

## **5\. Conceptual Data Model**

* **Users** (auth, profile, subscription status)  
* **Blueprints** (title, steps, tags, progress, created\_by)  
* **Resources** (title, type, source, difficulty, tags, sponsor\_id)  
* **SavedResources** (user\_id, resource\_id)  
* **Sponsors** (name, link, active, featured\_flag)

## **6\. UI/UX Principles**

* Inspired by StarterStory, but with lighter and more minimal design  
* Emphasize whitespace, content clarity, and subtle interactions  
* Design must feel calm, structured, and focused on productivity  
* Fast time-to-value: users should see a personalized plan in \< 5 minutes

## **7\. Security Considerations**

* Use Supabase RLS to secure user-specific data  
* Store OpenAI and Stripe keys securely (Supabase secrets \+ Vercel env)  
* Ensure role-based access for future admin tools  
* Email/password auth secured via Supabase Auth

## **8\. Development Phases**

### **Phase 1: Lean MVP (Weeks 1–6)**

* User auth (Supabase)  
* Survey onboarding flow  
* OpenAI integration  
* Create/manage blueprints  
* Basic resource saving  
* Stripe checkout integration  
* Admin panel for resource curation (future-proofing)

### **Phase 2: Full Launch (Weeks 7–12+)**

* Resource Library & Search  
* Google Drive export  
* Email onboarding & nudges  
* YouTube integration for video search  
* Subscription management features  
* Blueprint sharing & public modes (foundation for social)

## **9\. Potential Challenges**

* OpenAI content quality may vary → solution: use prompt templates \+ regeneration options  
* MVP cost control (OpenAI \+ Supabase quotas) → solution: usage limits for free users  
* Curating enough valuable resources → solution: manual curation \+ sponsor content

## **10\. Future Expansion Possibilities**

* Public blueprint library  
* Collaboration tools (shared learning plans)  
* Gamified progress tracking  
* Mentor matching system

