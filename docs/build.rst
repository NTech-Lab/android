********************************
Building App from Source Code
********************************

To build the FindFace demo app from source code (provided as an Android project), do the following:

#. Start :program:`Android Studio`. On the welcome screen, click :guilabel:`Import Project`.

     .. image:: _static/welcome.png
        :scale: 70%

#. Select the project folder. Click :guilabel:`OK`.

     .. image:: _static/select.png
        :scale: 70%

   Wait until the project is fully loaded, and :program:`Android Studio` is finished starting. This may take a while.

     .. image:: _static/loading.png
        :scale: 70%

   Once the progress bar at the bottom disappears, you are all set to start building the app.

     .. image:: _static/spinner.png
        :scale: 70%

#. To select the build variant, invoke the |green| :guilabel:`Build Variants` tool window. 

     .. |green| image:: _static/green.png
                :scale: 60%

     .. image:: _static/variants.png
        :scale: 70%

   Select the :guilabel:`masterRelease` build variant.

     .. image:: _static/master_release.png
        :scale: 70%

#. On the build panel, activate the :guilabel:`app` module.

     .. image:: _static/app_module.png
        :scale: 70%

#. In the main menu, navigate to :menuselection:`Build -->  Build APK`. It will launch building an APK of all the application modules in the current project.

     .. image:: _static/build.png
        :scale: 70%

   Wait until the build completes. Once it does, the progress bar at the bottom will disappear. The build will generate the ``app-master-release-v1.0.0.apk`` artifact.

     .. image:: _static/build_process.png
        :scale: 70%

#. To open the APK, click the :guilabel:`Event log` button at the bottom.

     .. image:: _static/event_log.png
        :scale: 70%


   On the tab that appears, click the ``Show in Explorer`` link.

     .. image:: _static/show.png
        :scale: 70%


You are now finished!
