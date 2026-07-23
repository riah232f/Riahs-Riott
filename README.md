Build a mobile app: RIOT — Full App Specification

Core Vibe & Aesthetic

• Dark theme throughout — deep blacks, charcoal, muted dark tones
• Per-user customizable background — each user can set their own subtle background (dark gradients, galaxy, storm clouds, ember glow, etc.)
• White starry border framing every screen — a thin, semi-transparent white border with tiny scattered stars (✧ ✦ ★) placed delicately along the top and bottom edges
• Stars can twinkle gently (slow opacity pulse) if animated — but work beautifully static too
• Overall feel: cozy, dreamy, night-sky atmosphere — like being inside a little universe



Navigation & Layout

Bottom Nav Tabs
1. Feed — main riot feed
2. YT Moots — your curated YouTube moot channels
3. Messages — private DMs and group chats
4. Profile — your profile, settings, creator controls

Top Bar
• Left: hamburger menu (☰) — settings, about, etc.
• Right: notification bell (🔔) with unread badge
• Small decorative star/sparkle accent



1. Feed Page ╭─ ✧ ─ ✦ ─ ★ ─ ✧ ─ ✦ ──────────╮
│  ☰                         🔔  ⊹ │
│                                  │
│  ˚ riahs riot ˚                  │
│  ⋆｡°✩ join the riot °｡⋆        │
│                                  │
│  ┌────────────────────────────┐  │
│  │  ⊹  RIRI'S STATUS  ⊹     │  │
│  │  (custom status message)  │  │
│  └────────────────────────────┘  │
│                                  │
│  ── ˚ riot feed ˚ ──            │
│                                  │
│  (scrollable feed of posts)      │
│                                  │
│  ...                             │
│                                  │
│                  [  +  ]         │
│           (create post FAB)      │
│                                  │
│  ── ✦ ─ ★ ─ ✧ ─ ✦ ─ ─         │
╰──────────────────────────────────╯
• FAB (floating action button) to create new posts
• Posts can include text, images, YouTube links with preview cards
• Infinite scroll

---

2. Private Messages & Group Chats

Entry Points
• Messages tab in bottom nav
• User profile → "Message" button
• In-feed "message" action on posts
• From YT Moots card → "Message"

One-to-One DMs
• Visible only to the two participants
• Dark theme, subtle panel with starry border
• Rounded message bubbles:
  • Your messages: aligned right, colored accent
  • Their messages: aligned left, semi-translucent white
• Timestamp and small avatar badge on each message
• Delivery states: sent ✓, delivered ✓✓, seen (blue ✓✓)
• Typing indicator: three-dot pulse animation
• Read receipts: optional, opt-in per user or global setting
• Message reactions: hold a message to react (heart, star, fire, laugh)

Supported Message Types
• Text
• Emoji / reactions
• Images (with optional compression/thumbnail)
• YouTube link preview (shows channel thumbnail, title, "Add to Moots" button)

Group Chats (GCs)
• Create groups with name, avatar, member selection
• Group size: small/collab-sized by default (open question — confirm max size)
• Admin/creator can:
  • Add/remove members
  • Change group name and avatar
  • Pin messages
  • Moderate
• Group info card: name, avatar, description, pinned posts, members list
• Invite flows: shareable invite link or in-app invite from follower list

Conversation List
• Shows unread badge counts (small, integrated into starry frame)
• Groups show a small stack of avatars
• Swipe left to mute, swipe right to archive
• Long-press for actions: pin, mute, delete

Composer
• Text input
• Emoji picker
• Attach image
• Send button

Privacy & Safety
• Messages encrypted at rest on servers
• Blocked users cannot send messages, mention you, or see you online
• Report flows: report message or report user → message ID, optional screenshots → moderation queue
• Automatic flagging for hate/harassment
• Leave group, mute notifications, block/report user(s), delete conversation from your view

Microcopy
• Empty state: "You don't have any chats yet. Tap the + to start a private chat or create a group!"
• Message search: quick search across conversations and within a conversation
• Message threading: simple replies (reply-to message showing a small quote)

---

3. YouTube Moots Page

Purpose
Your personal curated page for YouTube channels you add as "moots." Cute visual cards, quick access to their channel.

Entry Points
• "YT Moots" tab in bottom navigate • Quick-add "+ Add moot" button
• Inline "Add to Moots" button on YouTube link previews in chat and feed

Moot Card Design
• Semi-transparent dark plate with thin white starry border
• Elements:
  • Round channel avatar (left)
  • Channel name with @handle
  • Channel banner thumbnail (tiny) or channel tag icons (gaming, vlogs, etc.)
  • Quick stats line: small icons for uploads and recent activity
  • Action buttons: "Visit" (opens YouTube), "Message" (opens DM), "Remove" (with confirmation)
  • Cute micro-graphic: tiny star or ribbon indicating "moot" status
• Tapping Visit opens YouTube externally or in-app preview
• Reorder moots with drag handles
• Option to show a subset publicly on your profile as "My Moots" (toggle per channel)

Add / Manage Flow
• Add by @handle: type @ in "Add moot" box → app suggests matches → preview before adding
• Add from chat or channel mention: one-tap "Add to Moots"
• Bulk import option (optional): import a small list of handles
• Edit: add a short note for each moot (e.g., "collab buddy") visible only to you
• Notifications: optional "New upload from moot" toggle per channel

Page Layout
• Header: "Your YT Moots" with sparkle icon
• Grid/list toggle: 2-column card grid or stacked list
• Search & filter: by tag, recent upload, mutual follow
• Empty state: "No moots yet — add your YouTube friends by tapping + or by adding @handles"

Creator-Specific Features (You)
• Pin top moots to your public creator page
• Quick cross-post: share a moot's new upload as a riot post
• Highlight moots in your profile header (small row of avatars)

Polish
• Confetti + star animation when adding a moot
• "Mutual" badge if they follow you back
• "Moots" widget on profile showing 3 avatars framed by starry border

Moderation
• Respect "do not add" preferences if channels opt out
• Remove unwanted channels or block users
• Rate-limit invites to prevent spam

---

4. Background Music — Creator-Only Control

Concept
• Only you (the creator) can change the background music for the whole app
• Users hear whatever song you've set — they can see what's playing but can't change it
• UI is super minimal: by default it's just a tiny paw print 🐾 in the corner

For You (Creator) — Settings Panel ╭─────────────────────────────────────╮
│  ˚  app music  ˚                    │
│                                     │
│  ┌───────────────────────────────┐  │
│  │  🎵  currently playing         │  │
│  │  "soft rain" — chill lofi     │  │
│  │                               │  │
│  │  [  change song  ]            │  │
│  │                               │  │
│  │  your playlist:               │  │
│  │  ○ soft rain (lofi)           │  │
│  │  ○ midnight stars (ambient)   │  │
│  │  ○ cozy cafe (jazz hop)       │  │
│  │  ○ ember glow (acoustic)      │  │
│  │  ○ + add new                  │  │
│  │                               │  │
│  │  volume: ──────●───────       │  │
│  └───────────────────────────────┘  │
│                                     │
│  only visible to you ˚              │
╰─────────────────────────────────────╯ For Everyone — The Tiny Paw Print Player

Default state (collapsed):
• Tiny white paw print 🐾 sitting quietly in the bottom-right corner
• No text, no bar — super subtle, blends into the starry border
• When music is playing, the paw has a soft pulsing glow (barely noticeable opacity breathe)

When tapped — expands into a small card: ┌─────────────────────────────┐
│  🐾  ♪  now playing        │
│  "soft rain"               │
│  ──●───────  ⋆｡°✩         │
│  [  pause  ]  [  ♡  ]      │
└─────────────────────────────┘ • Paw print icon
• Song title
• Tiny progress bar with a star at the end
• Pause button
• Heart button (users can "like" the current song — you can see which are popular)
• Tap paw again or tap outside to collapse it back

Paw Print Icon Design
• Delicate white outline paw, slightly translucent
• Tiny star in the center pad
• Soft pulsing glow when music plays

Behavior Summary (you, creator can change the music , see the paw,  and sees expanded card ) (users, can not change the music, can see the paw, and see the expanded card)
---

5. Profile Page

• Your avatar, display name, bio, custom background
• "My Moots" widget (small row of 3 moot avatars)
• Your posts / activity feed
• Settings access
• Creator music control panel (only visible to you)

---

6. Settings & Creator Controls

• App Music — upload/pick tracks, manage playlist, set volume (you only)
• Notifications — per-conversation mute, global mute, upload alerts from moots
• Privacy — read receipts toggle, block list, report history
• Account — display name, avatar, bio, background
• About — app version, credits

---

7. Micro-Interactions & Animations

• Star twinkle on border elements
• Message bubble pop animation on send
• Typing indicator: three-dot pulse with tiny stars
• Paw print glow pulse when music plays
• Confetti + star burst when adding a moot
• Shimmer loading placeholders for images
• Subtle transitions between pages

---

8. Edge Cases & UX Details

• Empty states for every page (no messages, no moots, no posts)
• Error states: failed to send message, failed to load feed, network offline
• Loading states: shimmer animations, skeleton screens
• Blocked user: cannot message, cannot add as moot, cannot see each other's posts
• Deleted conversation: disappears from your list; other participant's copy remains
• Rate limits: prevents spam invites, rapid messaging
• Accessibility: high contrast text, large tappable areas, VoiceOver/TalkBack labels

---

9. Privacy & Security Summary

• Messages encrypted at rest
• End-to-end encryption noted as future enhancement
• Block/report flows for users and messages
• Automatic content flagging for hate/harassment
• Rate limiting and abuse throttles
• Moderation queue for reported content
• Opt-in read receipts
• "Do not add" preference for channels

---

10. Technical Notes (for devs)

• Messages DB table: conversation_id, participant list, timestamps, metadata, delivery status
• Attachments stored in object storage (S3 or equivalent) with signed URLs
• Moots mapping: user <-> YouTube handle; OAuth verification when possible
• Push notifications: in-app + push, user preferences respected
• Lazy-loading images, thumbnail caching
• Background music: audio files hosted on CDN, streamed to all active users

---

That's everything — from the starry borders down to the paw print player. You've got a full app spec ready to hand to a designer or dev team. ✧ ˚୨୧⋆｡˚
