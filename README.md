package org.firstinspires.ftc.teamcode;

import com.qualcomm.robotcore.eventloop.opmode.TeleOp;
import com.qualcomm.robotcore.eventloop.opmode.LinearOpMode;
import com.qualcomm.robotcore.hardware.DcMotor;
@TeleOp

public class Fatima5 extends LinearOpMode {
  @Override
  public void runOpMode(){
  
waitForStart();
while(opModeIsActive()){
  float x = this.gamepad1.left_stick_x;
  float y = this.gamepad1.left_stick_y * -1;
  telemetry.addData("Status", "x:" + x+ "y:" + y);
  telemetry.update();
  
}
    // todo: write your code here
} 
}
