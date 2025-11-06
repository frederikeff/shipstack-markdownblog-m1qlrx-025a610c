# MarkdownBlog

A clean, markdown-powered blogging platform with user authentication and threaded comments

## Project Vision

A simple blog platform with:
- User authentication
- Create and edit posts
- Markdown support
- Comments

## Tech Stack

**Frontend**: Next.js 14 + TypeScript + Tailwind CSS + ShadcnUI
**Backend**: Node.js + Express + PostgreSQL + Prisma ORM + JWT
**Deployment**: railway

## Features

1. **User Authentication System** - Email/password registration and login with JWT session management, password hashing with bcrypt, and protected routes
2. **Post Creation and Editing** - Rich markdown editor with live preview, draft saving, slug generation, and publish/unpublish functionality
3. **Markdown Rendering** - Client-side markdown parsing with syntax highlighting, sanitization to prevent XSS, and support for GFM features (tables, task lists)
4. **Public Post Listing** - Homepage displaying published posts with pagination, excerpt preview, author info, and publish date
5. **Single Post View** - Full post rendering with markdown content, author details, metadata, and comment section
6. **Comment System** - Threaded comments with nested replies, edit/delete for comment owners, and chronological sorting
7. **User Dashboard** - Personal dashboard showing user's posts with draft/published status, edit/delete actions, and post analytics
8. **Post Ownership Permissions** - Authorization middleware ensuring only post owners can edit/delete their content
9. **SEO Optimization** - Meta tags generation, Open Graph tags, structured data for posts, and sitemap generation
10. **Responsive Design** - Mobile-first responsive layout with optimized reading experience across all device sizes

## Status

This project is being built automatically by [ShipStack](https://shipstack.ai) AI agents.

- Jules: Building features
- Claude Code / Cursor: Testing and refining

---

Built with ShipStack 🚀
<!-- E2E Test Comment: e2e-test-1762435908286 -->
