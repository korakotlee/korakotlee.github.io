# Tasks: Modern Dashboard Design

**Feature Branch**: `001-modern-dashboard-design`
**Spec**: [spec.md](../spec.md)
**Plan**: [plan.md](../plan.md)

## Phase 1: Setup
- [x] T001 Create assets directory in assets/

## Phase 2: Foundational (Blocking)
- [x] T002 Update SCSS variables for Dark Theme in css/main.scss
- [x] T003 Define sidebar layout classes in css/main.scss
- [x] T004 Define animation keyframes and classes in css/main.scss

## Phase 3: Dashboard Layout Experience (P1)
**Goal**: Implement persistent sidebar and content grid.
**Test**: Verify sidebar exists and content is in a grid.

- [x] T005 [US1] Update default layout for sidebar structure in _layouts/default.html
- [x] T006 [US1] Update index page for grid layout in index.html
- [x] T007 [US1] Verify responsive sidebar behavior in css/main.scss

## Phase 4: Engaging Animations (P2)
**Goal**: Add smooth entrance and hover animations.
**Test**: Verify elements fade in and buttons scale/color shift on hover.

- [x] T008 [US2] Apply entrance animations to content in _layouts/default.html
- [x] T009 [US2] Add hover transitions for links and buttons in css/main.scss

## Phase 5: Visual Assets Integration (P3)
**Goal**: Add and display animated assets.
**Test**: Verify GIF loads and plays.

- [x] T010 [US3] Add animated GIF asset to assets/dashboard-preview.gif
- [x] T011 [US3] Display animated asset on dashboard in index.html

## Final Phase: Polish
- [x] T012 Verify all success criteria manually

## Dependencies
- US1 (Layout) blocks US2 (Animations) and US3 (Assets) visually, though implementation can overlap.
- Foundational CSS (T002-T004) blocks all UI tasks.

## Implementation Strategy
- Implement Dark Theme and CSS primitives first.
- Re-structure layout to sidebar/grid.
- Apply animations and assets last.
