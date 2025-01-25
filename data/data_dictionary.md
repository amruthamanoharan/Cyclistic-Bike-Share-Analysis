# Data Dictionary

This document explains the structure and meaning of the dataset used in the Cyclistic Bike-Share Analysis.

## Dataset Columns

1. **ride_id**:
   - Unique identifier for each ride.

2. **rideable_type**:
   - Type of bike used for the ride.
   - Possible values:
     - `electric_bike`: Electric-assisted bicycle.
     - `docked_bike`: Standard docked bicycle.
     - `classic_bike`: Standard classic bicycle.

5. **started_at**:
   - Timestamp indicating when the ride started (format: `YYYY-MM-DD HH:MM:SS`).

6. **ended_at**:
   - Timestamp indicating when the ride ended (format: `YYYY-MM-DD HH:MM:SS`).

7. **ride_duration_minutes**:
   - Duration of the ride in minutes (calculated as `ended_at - started_at`).

8. **member_casual**:
   - Rider type:
     - `member`: Annual subscriber.
     - `casual`: Non-subscriber or occasional user.

## Additional Notes
- The data covers bike-share activity from **May 2023 to April 2024**.
- The dataset has been anonymized to protect user privacy.
