# democollegeofhealth

A production-ready, highly scalable multi-portal College of Health Sciences and Technology Management System built with **Laravel 11**, **Livewire**, and **Tailwind CSS**. This platform is explicitly engineered to meet the unique structural and academic administrative standards of the Nigerian educational system.

## 🚀 Overview

`democollegeofhealth` consolidates a public-facing corporate website, an automated applicant admission processing framework, a comprehensive student management system, and an administrative command center into a single, high-performance ecosystem. 

Designed with a **mobile-first approach**, the platform ensures seamless navigation on smartphones—accommodating the primary browsing habits of Nigerian applicants and students—while utilizing cloud-optimized performance structures.

## 🌟 Key Features

### 🏢 1. Public Web Portal & CMS
*   **Modern Responsive Layout:** Sticky navigation header with an integrated mobile hamburger menu panel powered by Alpine.js.
*   **Dynamic Hero Slider:** Modern, auto-scrolling 5-image contextual carousel showcasing campus life, clinical laboratories, and practical health simulations.
*   **Dynamic Course Catalog:** Fully filterable dynamic courses list where each program redirects to a dedicated slugged page (`/courses/{slug}`) detailing:
    *   Comprehensive Course Descriptions.
    *   Explicit Academic Fees Structures (Application, Tuition, Lab Levies).
    *   Program Durations (e.g., 2-Year Diplomas, ND, HND).
    *   Standard Entry Criteria (e.g., 5 O'Level credits including English, Math, Biology, Chemistry, Physics).
    *   Post-Graduation Industry Career Paths.
*   **Automated Campus News Engine:** Real-time homepage news ticker/recent posts feed and dedicated paginated announcements archive automatically updated from the admin panel.

### 📝 2. Admission Process Portal (Applicants)
*   **Localization-Ready Registration:** Captures crucial Nigerian geographical and demographic criteria including State and LGA of origin.
*   **O'Level Grading Module:** Support for multi-sitting combinations (WAEC/NECO/NABTEB) with strict field criteria mapping.
*   **Stateful Workflow Engine:** Tracks applicant progression cleanly through sequential administrative pipelines: `Submitted` ➡️ `Under Review` ➡️ `Screening/Exam` ➡️ `Admitted` ➡️ `Accepted`.

### 🎓 3. Student Profile Dashboard
*   **Academic Portal:** Semester course registration mechanics, exam result publication logs, and GPA computing trackers.
*   **Financial Records:** Self-service digital invoices generation for school fees tracking, structured for fast integrations with payment gateways (e.g., Paystack/Remita hooks).

### 🛠️ 4. Central Admin Command Dashboard
*   **Real-time Analytics UI:** Aggregated summary metrics mapping total admissions throughput, revenue metrics, active staff roles, and course capacities.
*   **Core CMS Management:** Dedicated, rich-text backed CRUD tools handling the live Course Directory adjustments and automated Blog/Noticeboard updates.
*   **System Controls:** Batch-processing structures for admission clearing and automatic standard Matriculation Number sequence generation.

## 🛠️ Tech Stack & Architecture

*   **Backend Framework:** Laravel 11 (PHP 8.3+)
*   **Frontend Interface:** Blade + Livewire / Alpine.js (Reactive UI components)
*   **Styling Architecture:** Tailwind CSS (Mobile-first responsive grids)
*   **Database Management:** MySQL / PostgreSQL (Indexed foreign-key optimization with soft-deletes)
*   **Authentication Layout:** Secure Multi-Auth Guard system separating distinct system actors (`Admin`, `Staff`, `Student`, `Applicant`)

---
Developed with ❤️ for modern institutional management.

