# Doodle challenge notes:

## Initial requirements:

  - Build a chat interface in React + TypeScript
  - Display messages from multiple senders
  - Match the provided design mockup

### Tech Stack

  - React (required)
  - TypeScript (required)
  - Next.js or similar frameworks (optional)
  - Responsive across browsers and mobile devices

### API Integration

  - Backend: Frontend Challenge Chat API (separate repo)
  - Auth: Bearer token super-secret-doodle-token
  - Endpoints:
    - GET /api/v1/messages - Fetch messages (reverse chronological, pagination: after,
  limit)
    - POST /api/v1/messages - Send messages (fields: message, author)

### Time Constraint

  - ⏱️ 4-6 hours over one week

### Evaluation Criteria (what they care about)

  1. Code Quality - Readability, clean architecture
  2. Commits - Frequent, descriptive commits
  3. Performance - Fast load times, efficient mobile rendering
  4. Accessibility - User-friendly, accessible to everyone
  5. Design - Attention to detail (pixel-perfection NOT required)

### Submission

  - Email repo link to: code-challenge@doodle.com
  - Subject line: FE-<YourName>
  - Review timeline: ~1 week

## My notes:

  - **NextJS vs Vite + React**: Considered using NextJS for this challenge, since they use it in the company but it is not needed for this project. This is an SPA with no SEO requirements. I went with Vite + React because it fits perfectly the needs for this.
  -