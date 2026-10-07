# Water Save Campaign

Offline frontend college project using only HTML5, CSS3 and Vanilla JavaScript.

## Run
1. Extract `water-save-campaign.zip`.
2. Open `index.html` directly in a modern browser.
3. Register and log in.

## Features
- Registration/login with per-user localStorage data
- Protected single-section SPA navigation
- Water calculator and history
- 30 water-saving tips with completion tracking
- Saving goals with progress
- Wastage reporting with status tracking
- 30-question bank; 10 randomized questions per quiz
- Dashboard and CSS/JS usage chart
- Progress and profile
- Six local SVG pamphlets with modal preview
- Responsive desktop/tablet/mobile layout
- Toast notifications and accessibility-friendly labels

## Authentication limitation
The project uses browser localStorage for account and application data so it can run directly from index.html without a server.

## Storage
Data is namespaced per user:
- registeredUsers
- currentUser
- waterUsageRecords_<user id>
- waterSavingGoals_<user id>
- wastageReports_<user id>
- quizScores_<user id>
- completedTips_<user id>

No external APIs, backend, database, CSS framework or image URLs are required.
