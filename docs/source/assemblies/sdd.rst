System design description
===================================
Vacuum
-------
This section describes the vacuum design for Emerald. 

.. collapse:: Design criteria   
    
    Since the machine is supposed to operate at cryogenic temperature, a bakeout is not required. But it will be "good to have" feature if the machine is also operable at room temperature. Thus, we strive to design an :iabbr:`UHV (Ultra-high vacuum)` bakeable chamber which will achieve :iabbr:`XHV (Extremely-high vacuum)` once it is cooled down. 
    Of course for MAGIC, all components must be non-magnetic and magnetic shielding must be incorporated.

.. collapse:: Outer chamber
    
    The outer chamber is constructed in several parts for easier assembly.
    
    - Re-entrant window: Custom built fused-silica window to reduce the distance of dection objective lens to the ion trap center.
    - Bottom plate: This will be mounted on the optical table and should not deform under the weight of all components attached above it. The reentrant window for detection will be attached from below to this plate.
    - Bottom chamber: This part will have eight windows to allow laser entry-exit.
    - Top chamber: This part will have eight ports for attaching vacuum pumps, gauge, SMA connections, Sub-D connections and provision for future optical fiber connections.
    - Top plate: The cryocooler will be inserted through this flange. It will have provision for mounting to external crane/pulley system on top.
     
    
.. collapse:: Vacuum pumps and gauge
     
     The initial pump-down will be carried out via Turbo molecular pump (TMP). After reaching ~$10^-8$ mbar, the TMP will be disconnected from the chamber by closing the angle valve and NextTorr NEG+Ion pump will be switched on.
     The strength of Ion+NEG pump was decided based on the volume of the vacuum chamber and desired final vacuum.
     
         
    
    
    
    
    
    
    
----
 MW
----
----
RF
----   
---------
Detection
---------