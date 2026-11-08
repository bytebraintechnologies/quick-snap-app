# Quick Snap features

## Capture

- Capture a freeform region, monitor, or top-level application window.
- Select windows directly from a frozen desktop without bringing them to the front.
- Step through overlapping windows to capture an obscured window.
- Reuse the previous region or window selection and position it around the pointer.
- Capture scrolling content with automatic overlap matching and stitching on Windows.
- Use configurable global shortcuts, including `F1` and `PrintScreen` on Windows.
- Copy, save, pin, or open a capture in the editor directly from the selection overlay.
- Draw basic shapes on the selection before copying or saving it.
- Inspect precise pixels and desktop coordinates with the capture magnifier.

## Annotation editor

- Draw rectangles, ellipses, lines, arrows, freehand strokes, polygons, and highlighters.
- Add text boxes, text callouts, magnifier callouts, measurement lines, and highlight frames.
- Use curved and elbow connectors with joining points.
- Place numbered steps, status symbols, vector symbols, review stamps, sign-here tags, and business
  stamps.
- Insert clipboard images as movable and resizable objects.
- Blur, pixelate, mosaic, crop, and apply opt-in opaque redaction.
- Add a crop-safe watermark.
- Move and resize objects non-destructively with undo and redo.
- Snap objects to canvas and object edges or centers with visible alignment guides.
- Apply a presentation frame with padding, gradient background, rounded corners, and shadow.
- Keep the original capture unchanged while rendering annotations during copy and export.

## Screen pen

- Draw over every monitor on the live desktop or on a frozen screen.
- Use pen, highlighter, line, arrow, rectangle, and ellipse tools.
- Choose stroke widths and colors from a movable toolbar.
- Freeze or unfreeze the desktop without losing the drawing.
- On Windows, pass mouse and keyboard input through to applications beneath the drawing.
- Undo, redo, save the current screen, or save all screens.

## Screen recording

- Record a selected screen region with optional audio.
- Use bundled FFmpeg support in portable packages.
- Export and manage recordings through the same desktop workflow.

## Pinned captures and history

- Pin captures as borderless reference windows.
- Drag, zoom around the pointer, rotate, mirror, and adjust opacity.
- Toggle always-on-top and copy a pinned image back to the clipboard.
- Reopen recent captures from local history.
- Quick-save repeated captures using persisted preferences.

## Export and clipboard

- Copy flattened captures directly to the clipboard.
- Save PNG, optimized PNG, JPEG, WebP, BMP, and PDF output where supported by the workflow.
- Preserve PNG metadata used by Quick Snap workflows.
- Export framed or plain images without changing the history copy.

## Desktop integration

- Starts in the system tray with quick access to snip, repeat, screen pen, recording, history,
  preferences, restart, and quit.
- Persists shortcuts, appearance, capture behavior, quick-save location, and editor preferences.
- Uses native capture and permission flows for Windows, macOS, and Linux.
- Supports Windows x64 and ARM64 portable builds and Linux x64 previews.
- Includes macOS and Linux capture adapters, with native validation and distribution packaging still
  evolving.

## Privacy and resilience

- Processes screenshots, recordings, clipboard data, annotations, and exports locally.
- Does not include advertising or application-usage telemetry.
- Rotates diagnostic logs without recording capture or clipboard content.
- Reports permission, platform, and dependency failures with actionable messages.
