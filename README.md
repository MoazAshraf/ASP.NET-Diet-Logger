# ASP.NET Diet Logger
A diet logger built with ASP.NET and other technologies.

## Basic Requirements:
- The user can:
  - Add new food items
  - Add or edit nutrition facts for food items
  - Log their meals (breakfast, lunch, supper, snacks), this includes the time of the day as well as items and amounts
  - Write notes about their bodies and how they feel each day
- Track daily calories, protein, fat, carbs, fiber, vitamins, etc.
- Set targets for calories, protein, etc.
- Track hours of sleep

## Architecture:
I chose a single-page application (SPA) architecture for the following reasons:
- The user interface has to be easily scalable for new features
- The application must expose an API for the possibility of a mobile app

## Technologies:
- .NET 5.0
- ASP.NET Core
- Angular
- SQL Server Compact