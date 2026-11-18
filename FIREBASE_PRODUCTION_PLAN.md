# Protected-backend implementation plan

Use Firebase Authentication for account creation, password reset, and session persistence; Cloud Firestore for profiles, reports, attendance, announcements, projects, and audit records; Cloud Storage for certificate/license files. Use custom claims for country_director and international_director. Enforce all permissions in Firestore and Storage rules, not only in the client.

Minimum acceptance tests: unauthorized report query denied; non-director private comment denied; non-owner document denied; suspended account denied; audit timestamps server-generated; report owner cannot edit locked report; confidential storage URL not public.
