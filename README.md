lcls-plc-mfx-be-lens-interlock
==============================

MFX Beryllium Lens Interlock PLC code.

**Warning**
-----------

* This PLC code is part of a safety interlock. The LCLS Safety Office needs to be
  contacted prior to loading any changes on the PLC.
* ``ioc-mfx-tfs-lens`` is the corresponding EPICS IOC code for this PLC.  Prior
  to pushing any changes to the running IOC, the LCLS Safety Office must be
  contacted.
* Attenuator 11 of ``ioc-mfx-lusiAtt`` shall not be disabled, as it is an
  integral part of this safety interlock: it is being used as a beam shutter.

Related repositories
--------------------

* [transfocate](https://github.com/pcdshub/transfocate)
* [ioc-mfx-tfs-lens](https://github.com/pcdshub/ioc-mfx-tfs-lens/)
