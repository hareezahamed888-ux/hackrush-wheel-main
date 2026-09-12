# TODO — Two-Round Wheel System

## Steps
- [x] Read project files (start.html, admin-portal.html, index.html)
- [x] Confirm plan with user

## start.html
- [x] Add Round 1 / Round 2 toggle panel
- [x] Add second identical wheel (same look/properties)
- [x] Each wheel uses its own sentence list (app_settings id=1 / id=2)
- [x] Each wheel saves its own result (wheel_result_1/result_sentence_1, wheel_result_2/result_sentence_2)
- [x] Legend reflects active round

## admin-portal.html
- [x] Add Round 1 and Round 2 result columns to participant records
- [x] Add Round 1 / Round 2 toggle for separate sentence editors
- [x] Save Round 2 sentences to app_settings id=2

## Notes (Action required by user)
- [ ] Supabase `participants` table needs columns: wheel_result_1, result_sentence_1, wheel_result_2, result_sentence_2
- [ ] Supabase `app_settings` needs a row with id=2

