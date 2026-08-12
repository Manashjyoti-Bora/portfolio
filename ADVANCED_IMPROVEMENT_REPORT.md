# Advanced Improvement Report

## Additional polish pass
- Removed the dangling contact separator after the phone number was removed.
- Kept phone number privacy intact.
- Added a small hero rendering optimization (`will-change`) for smoother transform/compositing.
- Compressed oversized avatar/thumb/favicon assets without changing public paths.
- Preserved hero cutout PNG alpha and previous scale/position tuning.

## Validation target
- Build should pass.
- No phone number or tel links should appear.
- No public batch-year wording should appear.
- Live site should keep the latest hero scale and transparent PNG.
