# Data model

Production collections: users, profiles, reports, reportComments, reportAudit, mondayPrograms, attendance, announcements, announcementReads, projects, projectMembers, tasks, documents, documentAudit.

Required server timestamps: user.createdAt, report.submittedAt, report.updatedAt, review.reviewedAt, attendance.recordedAt, announcement.publishedAt, audit.createdAt.

Public profile and private administrative profile must be separate records. Passwords and Director codes must never be stored in profile records. Confidential files belong in protected object storage, never the GitHub repository.
