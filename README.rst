****************
Caliper Tracking
****************


Description
###########

Caliper Tracking can be used to transform the edx traditional event logs into `IMS Caliper Standard <http://imsglobal.org/sites/default/files/caliper/v1p1/caliper-spec-v1p1/caliper-spec-v1p1.html>`_ format. Then those logs can be used with any analytics application that is compatible with Caliper Standard events.

Installation
############

To install **caliper-tracking** in your Open edX installation add the following inside your requirements file. (For most Open edX installations it is located at edx-platform/requirements/edx/base.txt)::

    caliper-tracking==0.9.0


Usage
#####

To enable and use `caliper-tracking`

Set the value of ``ENABLE_EVENT_CALIPERIZATION``
flag in ``FEATURES`` in the following files:

 * ``/edx/app/edxapp/lms.env.json``
 * ``/edx/app/edxapp/cms.env.json``

which are located at ``/edx/app/edxapp/`` directory::


    "FEATURES": {
        ...

        "ENABLE_EVENT_CALIPERIZATION": true,

    }


Location of Transformed Logs
****************************

Transformed event logs can be found in `/edx/var/logs/tracking/tracking.log`.


License
#######

The code in this repository is licensed under
the AGPL 3.0 unless otherwise noted.

Please see `LICENSE <./LICENSE>`_ for details.


How To Contribute
#################

To contribute make PR in this repositry on Github : `Caliper Tracking <https://github.com/ucsd-ets/caliper-tracking>`_

If you have any issues, or questions, please feel free to open an issue on Github: `Caliper Tracking <https://github.com/ucsd-ets/caliper-tracking>`_


Contributors
############

* `Muhammad Zeeshan <https://github.com/zee-pk>`_
* `Saad Ali <https://github.com/NIXKnight>`_
* `Husnain Raza Ghaffar <https://github.com/HusnainRazaGhaffar>`_
* `Aroosha Arif <https://github.com/arooshaarif>`_
* `Osama Arshad <https://github.com/asamolion>`_
* `Tehreem Sadat <https://github.com/tehreem-sadat>`_
* `Muhammad Arslan <https://github.com/arslanhashmi>`_
* `Danial Malik <https://github.com/danialmalik>`_
* `Hamza Farooq <https://github.com/HamzaIbnFarooq>`_
* `Hassan Tariq <https://github.com/imhassantariq>`_
* `Muhammad Umar Khan <https://github.com/mumarkhan999>`_