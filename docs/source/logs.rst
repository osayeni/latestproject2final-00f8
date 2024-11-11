Latest Logs From Latest Build
==============================

Generated On: 2024-11-11 17:04:01 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/osayeni/newsamuelprj2/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-11_17:00:44] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-11_17:00:49] STEP 2: Create topics started

  [INFO 2024-11-11_17:01:24] STEP 2: Completed

  [INFO 2024-11-11_17:01:35] STEP 3: producing data started

  [INFO 2024-11-11_17:01:40] MQTT connection established...

  [INFO 2024-11-11_17:01:41] STEP 4: Preprocessing started

  [INFO 2024-11-11_17:01:46] STEP 4: Preprocessing started

  [INFO 2024-11-11_17:01:48] STEP 7: Visualization started

  [WARN 2024-11-11_17:02:02] STEP 7: Cannot make a connection to Viperviz on port 9005.  Going to try again...

  [INFO 2024-11-11_17:02:07] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-11_17:02:32] STEP 9: Starting privateGPT

  [INFO 2024-11-11_17:02:50] STEP 8: Starting docker push for: osayeni/latestproject2final-00f8-amd64

  [INFO 2024-11-11_17:02:57] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all --env PORT=8001 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-11_17:03:14] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 889c0e6684bd osayeni/latestproject2final-00f8-amd64 - message=0

  [INFO 2024-11-11_17:03:51] STEP 8: Successfully ran Docker push: docker push osayeni/latestproject2final-00f8-amd64 - message=0

  [INFO 2024-11-11_17:04:01] STEP 10: Started to build the documentation

  [INFO 2024-11-11_17:04:02] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


