# Unity Gameplay Systems Lab

A personal Unity lab where I build small, runnable prototypes to keep learning and explore gameplay systems in a focused way.

The labs are small and isolated (new scene + scripts) so I can try ideas quickly, test them, and take notes on what worked. Sometimes the goal is to recreate a tiny piece of "feel" from a game I like, sometimes it's to practice a system pattern, and sometimes it's just to answer a question like: "What's the cleanest way to structure this in Unity?"

## What you’ll find here

Each lab is a self-contained folder with:
- a runnable Unity scene
- the scripts used for that lab
- minimal assets (usually primitives + simple UI)

Topics I tend to explore:
- interaction mechanics and state
- UI feedback and simple HUDs
- lightweight AI/state machines
- data-driven patterns (ScriptableObjects)
- performance-minded patterns (ex: object pooling, reusing objects instead of constantly creating/destroying them)
- 3D math fundamentals (vectors, dot/cross, local vs world space)
- movement / physics feel tuning (accel/decel, damping, small “juice” touches)

## Start here (recommended labs)

Once there are a few labs in the repo, I'll keep a short "best of" list here for quick browsing:
- TBD

## Quick start

1. Clone the repo.
2. Open Unity Hub → Add project from disk.
3. Select the repo folder (the one containing `Assets/`, `Packages/`, and `ProjectSettings/`).
4. Open any lab scene from:
   `Assets/Labs/GameplaySystems/<YYYY-MM>/<YYYY-MM-DD_Type_ShortName>/Scenes/`

> Note: Unity will regenerate `Library/` locally on first open. That folder is intentionally not tracked in git.

## Repo layout

```text
Assets/
  Labs/
    GameplaySystems/
      YYYY-MM/
        YYYY-MM-DD_Type_ShortName/
          Scenes/
          Scripts/
          Prefabs/    (optional)
          UI/         (optional)
      Shared/
        Scripts/      (small utilities I may reuse)
        Prefabs/      (optional)
Packages/
ProjectSettings/
```

Each lab is one of the following types:
1. **Build** - implement a small feature
2. **Debug** - reproduce and fix a bug  
3. **Explain** - sketch and explain a system, then implement the smallest slice

## Notes

Short notes for each lab (what it is, controls, and how I tested it) live in: `LAB_NOTES.md`

---

Portfolio: https://www.lukemaeser.com