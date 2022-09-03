# README #

This README would normally document whatever steps are necessary to get your application up and running.

# installing requirements:

`pip3 install --upgrade odrive`

# motor setup

AT2814 motors configuration is 12N14P kv900 has 14 permanent poles to we do:
`odrv0.axis0.motor.config.pole_pairs = 7`

`odrv0.axis0.motor.config.torque_constant = 8.27/900`

`odrv0.axis0.motor.config.motor_type = MOTOR_TYPE_HIGH_CURRENT`

`odrv0.axis0.encoder.config.cpr = 16384`


For debugging:
`dump_errors()`

