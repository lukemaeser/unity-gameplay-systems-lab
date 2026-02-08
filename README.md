# Unity Gameplay Systems Lab

A personal Unity lab where I build small, runnable prototypes to keep learning and explore gameplay systems in a focused way.

Each lab is small and isolated (new scene + scripts) so I can try an idea quickly, test it, and capture what worked. Sometimes I'm recreating a tiny piece of "feel" from a game, sometimes I'm practicing a system pattern, and sometimes I'm answering a question like: "What is the cleanest way to structure this in Unity?"

## What you’ll find here

Each lab is a self-contained folder with:
- a runnable Unity scene
- the scripts used for that lab
- minimal assets (usually primitives + simple UI)

Topics I tend to explore:
- interaction mechanics and state
- UI feedback and simple HUDs
- lightweight AI and state machines
- data-driven patterns (ScriptableObjects)
- performance-minded patterns (object pooling, avoiding unnecessary allocations)
- 3D math fundamentals (vectors, dot/cross, local vs world space)
- movement and feel tuning (accel/decel, damping, small "juice" touches)

## Start here (recommended labs)

Once there are a few labs in the repo, I'll keep a short "best of" list here:
- TBD

## Quick start

1. Clone the repo.
2. Open Unity Hub → Add project from disk.
3. Select the repo folder (the one containing `Assets/`, `Packages/`, and `ProjectSettings/`).
4. Open any lab scene from:
   `Assets/Labs/GameplaySystems/<YYYY-MM>/<YYYY-MM-DD_<Type>_<ShortName>>/Scenes/`

> Note: Use the Unity version listed in `ProjectSettings/ProjectVersion.txt`. Unity will regenerate `Library/` locally on first open (not tracked in git).

## Repo layout
```text
Assets/
  Labs/
    GameplaySystems/
      YYYY-MM/
        YYYY-MM-DD_<Type>_<ShortName>/
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
- **Build** - implement a small feature
- **Debug** - reproduce and fix a bug
- **Explain** - sketch and explain a system, then implement the smallest slice

## Notes

Short notes for each lab (what it is, controls, and how I tested it) live in: `LAB_NOTES.md`

---

Portfolio: https://www.lukemaeser.com