/***********************************************************************************
 *          RobotGeek Linear Actuator Demo   
 *          Incremental Analog Control             
 *  
 *    
 *  The following sketch will allow you to control a Firgelli Linear Actuator using
 *  a RobotGeek Joystick for incremental movement.
 *
 *  Products
 *    http://www.robotgeek.com/robotgeek-pantilt.aspx
 *    http://www.robotgeek.com/robotgeek-geekduino-sensor-kit
 *    http://www.robotgeek.com/robotgeek-joystick
 *    http://www.robotgeek.com/p/power-supply-6vdc-2a.aspx
 *    Firgelli Mini Linear Actuators http://www.robotgeek.com/store/Search.aspx?SearchTerms=firgelli
 *    
 *  Wiring
 *    Linear Actuatoro - Digital Pin 9 
 *    Joystick(Vertica)   - Analog Pin 0
 *    Jumper for pins 9/10/11 should be set to 'VIN'
 *  
 *
 *  Control Behavior:
 *    Moving the joysticks will incrementally move the linear actuator. This means that when you
 *    release the joystick to its 'home' position, the actuator will stay in the last place
 *    it was. This allows for incremental position control.
 *
 *  External Resources
 *
 ***********************************************************************************/