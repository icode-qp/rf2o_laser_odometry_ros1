This project fully references MAPIRlab/rf2o_laser_odometry and only fixes minor bugs that existed:

(1) Can't find the lookupTransform base_link to laser  

(2) Invalid argument passed to lookupTrasform argument source_frame in tf2 frame_ids cannot be empty

(3) Eigensolver couldn't find a solution. pose is not updated
