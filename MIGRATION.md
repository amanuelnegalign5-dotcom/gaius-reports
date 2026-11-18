# Migration

1. Back up the current application data before replacing files.
2. Preserve existing localStorage keys gUsers, gReports, gComments, gAttendance, and gLang.
3. Upload the new package files to the same GitHub Pages repository.
4. Do not clear Safari website data during migration.
5. When a backend is introduced, run a one-time authenticated import that maps local user IDs to backend user IDs, then verify record counts before disabling local writes.
