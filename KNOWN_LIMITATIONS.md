# Known limitations

This GitHub Pages package is a local-first PWA prototype. GitHub Pages has no secure database, server-side authorization, private-file storage, or cross-device synchronization. Local browser data can be read by anyone with access to the same device profile. Therefore confidential documents, real production identities, and sensitive addresses must not be used until Firebase, Supabase, or Microsoft Entra ID/Dataverse is connected and security rules are tested.

The UI can demonstrate roles, reports, attendance, profiles, and dashboards locally, but local JavaScript checks are not production security controls.
