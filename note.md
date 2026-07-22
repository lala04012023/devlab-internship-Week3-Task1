# NYC Taxi Time-Based Analysis

## Dataset Overview
- Loaded the NYC taxi trip dataset.
- Converted pickup_datetime to datetime format.
- Converted trip_duration from seconds to minutes.

## Data Cleaning
- Removed trips shorter than 1 minute.
- Removed trips longer than 120 minutes.

## Feature Engineering
Created the following features:
- Hour of day
- Day of week
- Month

## Time-Based Analysis
- Calculated trip count by hour.
- Identified peak and off-peak hours.
- Compared weekday and weekend demand.
- Calculated average trip duration by hour.
- Analyzed monthly trip counts.

## Visualizations
- Trips by Hour (Line Chart)
- Trips by Weekday (Bar Chart)
- Trip Duration Distribution (Histogram)
- Monthly Trip Count (Bar Chart)

## Operational Insights
1. Peak-hour demand highlights the periods when additional taxis may be required.
2. Weekday and weekend demand patterns differ, supporting separate driver scheduling strategies.
3. Average trip duration varies throughout the day, reflecting changing traffic conditions.
4. Monthly demand trends can assist in fleet management and operational planning.

--------------------------------------------------------------------------------
1. Pik saatlarda taksi tələbatının artması əlavə taksilərin xidmətə cəlb edilməsinin zəruri ola biləcəyini göstərir.
2. Həftəiçi və həftəsonu günlərində taksi tələbatı fərqləndiyi üçün sürücülərin iş qrafiki bu fərqlər nəzərə alınaraq planlaşdırıla bilər.
3. Günün müxtəlif saatlarında orta səfər müddəti dəyişir ki, bu da yol hərəkətinin intensivliyi və tıxacların təsirini əks etdirir.
4. Aylıq tələbat tendensiyaları taksi parkının idarə olunması və əməliyyat planlaşdırılmasının daha səmərəli həyata keçirilməsinə kömək edə bilər.
