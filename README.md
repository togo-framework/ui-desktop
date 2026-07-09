<!-- togo-header -->
# @togo-framework/ui-desktop

OS-like desktop shell on top of the `os` plugin: dock, window manager,
spotlight, launchpad, notification center, and a lock/login screen. Part of
the togo UI kit.

```bash
npm install @togo-framework/ui-desktop
```

```tsx
import { DesktopShell, WindowManagerProvider } from "@togo-framework/ui-desktop";
```

Requires `@togo-framework/ui-core` and `@togo-framework/ui-auth` (the login
screen reuses the shared LockScreen/PasswordLockScreen components).
<!-- togo-sponsors -->
