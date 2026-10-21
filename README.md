# Ravuri Charan Teja — Developer Portfolio

A responsive portfolio for **Ravuri Charan Teja**, a Software Product Engineering student focused on full-stack development, backend workflows, Java, DSA and practical product engineering.

The portfolio presents project context, implementation details, technology choices, role or collaboration context, and source/live links where available.

## Profile

- B.Tech Computer Science and Engineering, Software Product Engineering through Kalvium
- CGPA: 8.98/10; expected graduation: July 2029
- Java: 6 of 7 Dojo belts; Python: 4 Dojo belts
- Communication score: 8
- Focus: full-stack products, backend/API development, testing, AI integrations and problem solving

## Projects

### Heaven-Bus — real-time bus booking
Five-minute seat holds, transaction-backed seat allocation, payment verification and recovery, trip search and passenger/admin workflows. Ask Jarvis combines route discovery with issue-specific support contacts; free-form Ollama answers are used in local development while booking facts remain deterministic.

- [Live site](https://heaven-bus-web.onrender.com/)
- [Repository](https://github.com/charanteja7725/Heaven-Bus)

### LeadPilot — AI sales outreach assistant
A human-reviewed workflow for turning B2B lead facts into a fit assessment, an initial email and two follow-ups. Includes Gemini integration, structured output validation with Zod and provider-stubbed backend tests. It does not send emails automatically.

- [Live site](https://leadpilot-mauve.vercel.app/)
- [Repository](https://github.com/charanteja7725/LeadPilot-s)

### AgroConnect 2.0 — agricultural marketplace
A multi-role marketplace for buyers, farmers, fertilizer sellers, delivery partners, area verification employees and administrators. Features include verification-gated produce publishing, orders, delivery workflows, notifications and media handling.

- [Live site](https://agro-connect2-0-iiq5.vercel.app/)
- [Repository](https://github.com/charanteja7725/AgroConnect2.0)

### Rangam Saree Silks — e-commerce
A full-stack saree storefront with authentication, product and order APIs, Cloudinary media uploads and Razorpay payment integration.

- [Live site](https://rangam-saree-silks.vercel.app/)
- [Repository](https://github.com/charanteja7725/rangam-saree-silks)

### WardClean — hospital housekeeping tasks and compliance
Flutter and Firebase MVP for employee task completion and supervisor oversight, with real-time task updates, photo issue reports and compliance summaries.

- [Live site](https://ward-clean-54a66.web.app/)
- [Community repository](https://github.com/kalviumcommunity/Housekeeping-Task-Manager-kalvium_community)

### SkillXchange — peer learning and mentorship
A collaborative learning platform combining WebRTC sessions, a shared whiteboard, AI-assisted tutoring and document analysis, learning roadmaps and study groups.

- [Live site](https://skillxchange-cp.vercel.app/)
- [Project repository](https://github.com/cherukuriyogini/SKILLXCHANGE-CP)

### Flipkart Smart Wishlist — team e-commerce project
Next.js and PostgreSQL project with wishlist stock synchronization, optimistic wishlist-to-cart updates, transactional checkout, order flows and admin inventory tools.

- [Community repository](https://github.com/kalviumcommunity/FLIPKART-WISHLIST_kalvium-community)

### Food Donation — MERN application
Connects donors and recipients through donation listings, location and quantity details, real-time updates, and request/claim workflows.

- [Repository](https://github.com/charanteja7725/fooddonation)

### NoSQL CRUD API — documented backend service
Express and MongoDB REST API with centralized error handling, Swagger endpoint documentation and a Postman collection for user CRUD operations.

- [Live API](https://nosql-api-5.onrender.com/)
- [Swagger docs](https://nosql-api-5.onrender.com/api-docs)
- [Repository](https://github.com/charanteja7725/nosqL-api)

### Tata 1mg — collaborative project
Kalvium team project with backend/API contribution, Next.js architecture and frontend/backend integration. The team used review feedback to debug and rebuild the submission.

- Collaborative project; no public repository or live link is listed.

## Architecture and performance

The site uses semantic HTML, CSS and a small vanilla JavaScript interaction layer.

- No Three.js, WebGL or continuous canvas rendering
- CSS-only visual depth and pointer-only card tilt
- IntersectionObserver-based one-time reveals and section tracking
- One passive scroll listener for the compact header state
- `prefers-reduced-motion` support
- Content remains visible if JavaScript fails
- Responsive desktop, tablet and mobile layouts

## Run locally

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.
