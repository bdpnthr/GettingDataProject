## 📑 CodeBook.md

```markdown
# CodeBook

## Data Source
Human Activity Recognition Using Smartphones Dataset
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## Variables
- **subject**: ID of the subject (1–30).
- **activity**: Activity performed (e.g., WALKING, SITTING).
- **measurements**: Mean and standard deviation values from accelerometer and gyroscope signals.

## Transformations
1. Training and test sets merged.
2. Extracted only mean and standard deviation features.
3. Replaced activity codes with descriptive names.
4. Cleaned variable names:
   - `Acc` → `Accelerometer`
   - `Gyro` → `Gyroscope`
   - `Mag` → `Magnitude`
   - Prefix `t` → `Time`
   - Prefix `f` → `Frequency`
   - Removed duplicates (`BodyBody` → `Body`)
5. Created tidy dataset with averages grouped by subject and activity.
