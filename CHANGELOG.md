# CHANGELOG

1.0.2

* Just ensure deleted_at IS NULL is _somewhere_ in the partial index condition

1.0.1

* Include schema name in join to stop getting false positives

1.0.0

* The previous version ran inside transactions and failed 99.999% of the time. We've had broken
  things in our projects for three years.
