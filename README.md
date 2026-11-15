# garmin-run-watch

Latest run analysis for the ManRunAnalysis watch app on a Garmin Forerunner 965.

`run.json` is rebuilt after each run from the run skill's analysis. It contains
only per-km pace, heart rate, cadence, temperature and altitude, plus a few
short training notes. No GPS track, no run name, no location, no personal
details — the file on its own does not identify where the run happened.

The watch app fetches `run.json` over HTTPS through the paired phone
(Garmin Connect Mobile). It is a public file so the watch can fetch it
without signing in.
