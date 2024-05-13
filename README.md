# DAP-Project
ETL and Data Analysis for Chicago City Car Crash Data

Data Sets Used:
Motor Vehicle Collisions - Crashes: https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes
Traffic Crashes - People: https://catalog.data.gov/dataset/traffic-crashes-people
Traffic Crashes - Vehicles: https://catalog.data.gov/dataset/traffic-crashes-vehicles

-------------------------------------------------------------------------

To run the code download the files or git pull and run the command
docker compose up

Once the container is running go to 127.0.0.1:3000 to access the dagster ETL dashboard
launch a run by clicking on the 'run' tab and and launching a run.

Once the ETL is completed start the 'plotly' container and go to 127.0.0.1:8050 to access the dashboard


--------------------------------------------------------------------------

Known issues:
The first ETL run may throw an error. Just re-execure the launch.
