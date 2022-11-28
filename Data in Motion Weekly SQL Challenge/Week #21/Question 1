--How many runners signed up for each 1 week period?

SELECT
	DATE_PART('week',registration_date) AS registration_week,
    COUNT(runner_id) AS new_registrations
FROM pizza_runner.runners

GROUP BY registration_week
