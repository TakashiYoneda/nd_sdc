# nd_sdc_p1
udacity_nano-degree_self-driving-car



detect edge in image (gray, GaussianBlur, Canny)
delete noise
  masking image area 
separate (left and right lines by tangent)
 
extrapolate lines
  detect lines (HoughLineP)
  masking tangent, interception of lines
  carrying tangent for extrapolation
  
  draw line (Line)

still have a noise effect
shadow, road color, tire-slip mark, line color dilusion, road curve, 

in the real world, there should be lots of obstacle for clear detection of targets
sensors
