# 

# dump

# version
# Betaflight / MATEKF405 (MKF4) 4.1.1 Nov 15 2019 / 12:34:32 (1e5e3d369) MSP API: 1.42

# start the command batch
batch start

board_name MATEKF405
manufacturer_id 

# name: Darwin129

# resources
resource BEEPER 1 C13
resource MOTOR 1 C06
resource MOTOR 2 C07
resource MOTOR 3 C08
resource MOTOR 4 C09
resource MOTOR 5 A15
resource MOTOR 6 A08
resource MOTOR 7 B08
resource MOTOR 8 NONE
resource SERVO 1 NONE
resource SERVO 2 NONE
resource SERVO 3 NONE
resource SERVO 4 NONE
resource SERVO 5 NONE
resource SERVO 6 NONE
resource SERVO 7 NONE
resource SERVO 8 NONE
resource PPM 1 A03
resource PWM 1 A00
resource PWM 2 A01
resource PWM 3 A02
resource PWM 4 NONE
resource PWM 5 NONE
resource PWM 6 NONE
resource PWM 7 NONE
resource PWM 8 NONE
resource LED_STRIP 1 B06
resource SERIAL_TX 1 A09
resource SERIAL_TX 2 A02
resource SERIAL_TX 3 C10
resource SERIAL_TX 4 A00
resource SERIAL_TX 5 C12
resource SERIAL_TX 6 NONE
resource SERIAL_TX 7 NONE
resource SERIAL_TX 8 NONE
resource SERIAL_TX 9 NONE
resource SERIAL_TX 10 NONE
resource SERIAL_TX 11 NONE
resource SERIAL_TX 12 NONE
resource SERIAL_RX 1 A10
resource SERIAL_RX 2 A03
resource SERIAL_RX 3 C11
resource SERIAL_RX 4 A01
resource SERIAL_RX 5 D02
resource SERIAL_RX 6 NONE
resource SERIAL_RX 7 NONE
resource SERIAL_RX 8 NONE
resource SERIAL_RX 9 NONE
resource SERIAL_RX 10 NONE
resource SERIAL_RX 11 NONE
resource SERIAL_RX 12 NONE
resource I2C_SCL 1 B06
resource I2C_SCL 2 NONE
resource I2C_SCL 3 NONE
resource I2C_SDA 1 B07
resource I2C_SDA 2 NONE
resource I2C_SDA 3 NONE
resource LED 1 B09
resource LED 2 A14
resource LED 3 NONE
resource RX_BIND 1 NONE
resource RX_BIND_PLUG 1 NONE
resource SPI_SCK 1 A05
resource SPI_SCK 2 B13
resource SPI_SCK 3 B03
resource SPI_MISO 1 A06
resource SPI_MISO 2 B14
resource SPI_MISO 3 B04
resource SPI_MOSI 1 A07
resource SPI_MOSI 2 B15
resource SPI_MOSI 3 B05
resource ESCSERIAL 1 A03
resource CAMERA_CONTROL 1 NONE
resource ADC_BATT 1 C05
resource ADC_RSSI 1 B01
resource ADC_CURR 1 C04
resource ADC_EXT 1 NONE
resource BARO_CS 1 NONE
resource BARO_EOC 1 NONE
resource BARO_XCLR 1 NONE
resource COMPASS_CS 1 NONE
resource SDCARD_CS 1 C01
resource SDCARD_DETECT 1 NONE
resource PINIO 1 NONE
resource PINIO 2 NONE
resource PINIO 3 NONE
resource PINIO 4 NONE
resource USB_MSC_PIN 1 NONE
resource FLASH_CS 1 C00
resource OSD_CS 1 B10
resource GYRO_EXTI 1 C03
resource GYRO_EXTI 2 NONE
resource GYRO_CS 1 C02
resource GYRO_CS 2 NONE
resource USB_DETECT 1 B12
resource PULLUP 1 NONE
resource PULLUP 2 NONE
resource PULLUP 3 NONE
resource PULLUP 4 NONE
resource PULLDOWN 1 NONE
resource PULLDOWN 2 NONE
resource PULLDOWN 3 NONE
resource PULLDOWN 4 NONE

# timer
timer A03 AF2
# pin A03: TIM5 CH4 (AF2)
timer C06 AF2
# pin C06: TIM3 CH1 (AF2)
timer C07 AF3
# pin C07: TIM8 CH2 (AF3)
timer C08 AF3
# pin C08: TIM8 CH3 (AF3)
timer C09 AF3
# pin C09: TIM8 CH4 (AF3)
timer A15 AF1
# pin A15: TIM2 CH1 (AF1)
timer A08 AF1
# pin A08: TIM1 CH1 (AF1)
timer B08 AF2
# pin B08: TIM4 CH3 (AF2)
timer B06 AF2
# pin B06: TIM4 CH1 (AF2)
timer A00 AF2
# pin A00: TIM5 CH1 (AF2)
timer A01 AF2
# pin A01: TIM5 CH2 (AF2)
timer A02 AF3
# pin A02: TIM9 CH1 (AF3)

# dma
dma SPI_TX 1 NONE
dma SPI_TX 2 NONE
dma SPI_TX 3 1
# SPI_TX 3: DMA1 Stream 7 Channel 0
dma SPI_RX 1 NONE
dma SPI_RX 2 NONE
dma SPI_RX 3 NONE
dma ADC 1 0
# ADC 1: DMA2 Stream 0 Channel 0
dma ADC 2 NONE
dma ADC 3 NONE
dma UART_TX 1 NONE
dma UART_TX 2 NONE
dma UART_TX 3 NONE
dma UART_TX 4 NONE
dma UART_TX 5 NONE
dma UART_TX 6 NONE
dma UART_TX 7 NONE
dma UART_TX 8 NONE
dma UART_RX 1 NONE
dma UART_RX 2 NONE
dma UART_RX 3 NONE
dma UART_RX 4 NONE
dma UART_RX 5 NONE
dma UART_RX 6 NONE
dma UART_RX 7 NONE
dma UART_RX 8 NONE
dma pin A03 0
# pin A03: DMA1 Stream 1 Channel 6
dma pin C06 0
# pin C06: DMA1 Stream 4 Channel 5
dma pin C07 1
# pin C07: DMA2 Stream 3 Channel 7
dma pin C08 1
# pin C08: DMA2 Stream 4 Channel 7
dma pin C09 0
# pin C09: DMA2 Stream 7 Channel 7
dma pin A15 0
# pin A15: DMA1 Stream 5 Channel 3
dma pin A08 0
# pin A08: DMA2 Stream 6 Channel 0
dma pin B08 0
# pin B08: DMA1 Stream 7 Channel 2
dma pin B06 0
# pin B06: DMA1 Stream 0 Channel 2
dma pin A00 0
# pin A00: DMA1 Stream 2 Channel 6
dma pin A01 0
# pin A01: DMA1 Stream 4 Channel 6
dma pin A02 NONE

# mixer
mixer QUADX

mmix reset


# servo
servo 0 1000 2000 1500 100 -1
servo 1 1000 2000 1500 100 -1
servo 2 1000 2000 1500 100 -1
servo 3 1000 2000 1500 100 -1
servo 4 1000 2000 1500 100 -1
servo 5 1000 2000 1500 100 -1
servo 6 1000 2000 1500 100 -1
servo 7 1000 2000 1500 100 -1

# servo mixer
smix reset


# feature
feature -RX_PPM
feature -INFLIGHT_ACC_CAL
feature -RX_SERIAL
feature -MOTOR_STOP
feature -SERVO_TILT
feature -SOFTSERIAL
feature -GPS
feature -RANGEFINDER
feature -TELEMETRY
feature -3D
feature -RX_PARALLEL_PWM
feature -RX_MSP
feature -RSSI_ADC
feature -LED_STRIP
feature -DISPLAY
feature -OSD
feature -CHANNEL_FORWARDING
feature -TRANSPONDER
feature -AIRMODE
feature -RX_SPI
feature -SOFTSPI
feature -ESC_SENSOR
feature -ANTI_GRAVITY
feature -DYNAMIC_FILTER
feature RX_SERIAL
feature SOFTSERIAL
feature GPS
feature TELEMETRY
feature RSSI_ADC
feature LED_STRIP
feature OSD
feature AIRMODE
feature ANTI_GRAVITY
feature DYNAMIC_FILTER

# beeper
beeper GYRO_CALIBRATED
beeper RX_LOST
beeper RX_LOST_LANDING
beeper DISARMING
beeper ARMING
beeper ARMING_GPS_FIX
beeper ARMING_GPS_NO_FIX
beeper BAT_CRIT_LOW
beeper BAT_LOW
beeper GPS_STATUS
beeper RX_SET
beeper ACC_CALIBRATION
beeper ACC_CALIBRATION_FAIL
beeper READY_BEEP
beeper MULTI_BEEPS
beeper DISARM_REPEAT
beeper ARMED
beeper SYSTEM_INIT
beeper -ON_USB
beeper BLACKBOX_ERASE
beeper CRASH_FLIP
beeper CAM_CONNECTION_OPEN
beeper CAM_CONNECTION_CLOSE
beeper RC_SMOOTHING_INIT_FAIL

# beacon
beacon RX_LOST
beacon -RX_SET

# map
map AETR1234

# serial
serial 20 1 115200 57600 0 115200
serial 0 2 115200 115200 0 115200
serial 1 64 115200 57600 0 115200
serial 2 2048 115200 57600 0 115200
serial 3 0 115200 57600 0 115200
serial 4 1 19200 57600 0 115200

# led
led 0 0,0::CTOBVIW:0
led 1 0,1::CTOBVIW:0
led 2 0,2::CTOBVIW:0
led 3 0,3::CTOBVIW:0
led 4 1,0::CTOBVIW:0
led 5 1,1::CTOBVIW:0
led 6 1,2::CTOBVIW:0
led 7 1,3::CTOBVIW:0
led 8 0,0::C:0
led 9 0,0::C:0
led 10 0,0::C:0
led 11 0,0::C:0
led 12 0,0::C:0
led 13 0,0::C:0
led 14 0,0::C:0
led 15 0,0::C:0
led 16 0,0::C:0
led 17 0,0::C:0
led 18 0,0::C:0
led 19 0,0::C:0
led 20 0,0::C:0
led 21 0,0::C:0
led 22 0,0::C:0
led 23 0,0::C:0
led 24 0,0::C:0
led 25 0,0::C:0
led 26 0,0::C:0
led 27 0,0::C:0
led 28 0,0::C:0
led 29 0,0::C:0
led 30 0,0::C:0
led 31 0,0::C:0

# color
color 0 0,0,0
color 1 0,255,255
color 2 0,0,255
color 3 30,0,255
color 4 60,0,255
color 5 90,0,255
color 6 120,0,255
color 7 150,0,255
color 8 180,0,255
color 9 210,0,255
color 10 240,0,255
color 11 270,0,255
color 12 300,0,255
color 13 330,0,255
color 14 0,0,0
color 15 0,0,0

# mode_color
mode_color 0 0 1
mode_color 0 1 11
mode_color 0 2 2
mode_color 0 3 13
mode_color 0 4 10
mode_color 0 5 3
mode_color 1 0 5
mode_color 1 1 11
mode_color 1 2 3
mode_color 1 3 13
mode_color 1 4 10
mode_color 1 5 3
mode_color 2 0 10
mode_color 2 1 11
mode_color 2 2 4
mode_color 2 3 13
mode_color 2 4 10
mode_color 2 5 3
mode_color 3 0 8
mode_color 3 1 11
mode_color 3 2 4
mode_color 3 3 13
mode_color 3 4 10
mode_color 3 5 3
mode_color 4 0 7
mode_color 4 1 11
mode_color 4 2 3
mode_color 4 3 13
mode_color 4 4 10
mode_color 4 5 3
mode_color 5 0 0
mode_color 5 1 0
mode_color 5 2 0
mode_color 5 3 0
mode_color 5 4 0
mode_color 5 5 0
mode_color 6 0 6
mode_color 6 1 10
mode_color 6 2 1
mode_color 6 3 0
mode_color 6 4 0
mode_color 6 5 2
mode_color 6 6 3
mode_color 6 7 6
mode_color 6 8 0
mode_color 6 9 0
mode_color 6 10 0
mode_color 7 0 3

# aux
aux 0 0 0 1300 2100 0 0
aux 1 1 0 1300 2100 0 0
aux 2 13 3 1300 1700 0 0
aux 4 0 0 900 900 0 0
aux 5 0 0 900 900 0 0
aux 6 0 0 900 900 0 0
aux 7 0 0 900 900 0 0
aux 8 0 0 900 900 0 0
aux 9 0 0 900 900 0 0
aux 10 0 0 900 900 0 0
aux 11 0 0 900 900 0 0
aux 12 0 0 900 900 0 0
aux 13 0 0 900 900 0 0
aux 14 0 0 900 900 0 0
aux 15 0 0 900 900 0 0
aux 16 0 0 900 900 0 0
aux 17 0 0 900 900 0 0
aux 18 0 0 900 900 0 0
aux 19 0 0 900 900 0 0

# adjrange
adjrange 0 0 0 900 900 0 0 0 0
adjrange 1 0 0 900 900 0 0 0 0
adjrange 2 0 0 900 900 0 0 0 0
adjrange 3 0 0 900 900 0 0 0 0
adjrange 4 0 0 900 900 0 0 0 0
adjrange 5 0 0 900 900 0 0 0 0
adjrange 6 0 0 900 900 0 0 0 0
adjrange 7 0 0 900 900 0 0 0 0
adjrange 8 0 0 900 900 0 0 0 0
adjrange 9 0 0 900 900 0 0 0 0
adjrange 10 0 0 900 900 0 0 0 0
adjrange 11 0 0 900 900 0 0 0 0
adjrange 12 0 0 900 900 0 0 0 0
adjrange 13 0 0 900 900 0 0 0 0
adjrange 14 0 0 900 900 0 0 0 0
adjrange 15 0 0 900 900 0 0 0 0
adjrange 16 0 0 900 900 0 0 0 0
adjrange 17 0 0 900 900 0 0 0 0
adjrange 18 0 0 900 900 0 0 0 0
adjrange 19 0 0 900 900 0 0 0 0
adjrange 20 0 0 900 900 0 0 0 0
adjrange 21 0 0 900 900 0 0 0 0
adjrange 22 0 0 900 900 0 0 0 0
adjrange 23 0 0 900 900 0 0 0 0
adjrange 24 0 0 900 900 0 0 0 0
adjrange 25 0 0 900 900 0 0 0 0
adjrange 26 0 0 900 900 0 0 0 0
adjrange 27 0 0 900 900 0 0 0 0
adjrange 28 0 0 900 900 0 0 0 0
adjrange 29 0 0 900 900 0 0 0 0

# rxrange
rxrange 0 1000 2000
rxrange 1 1000 2000
rxrange 2 1000 2000
rxrange 3 1000 2000

# vtx
vtx 0 0 0 0 0 900 900
vtx 1 0 0 0 0 900 900
vtx 2 0 0 0 0 900 900
vtx 3 0 0 0 0 900 900
vtx 4 0 0 0 0 900 900
vtx 5 0 0 0 0 900 900
vtx 6 0 0 0 0 900 900
vtx 7 0 0 0 0 900 900
vtx 8 0 0 0 0 900 900
vtx 9 0 0 0 0 900 900

# vtxtable
vtxtable bands 6
vtxtable channels 8
vtxtable band 1 BOSCAM_A A FACTORY 5865 5845 5825 5805 5785 5765 5745 5725
vtxtable band 2 BOSCAM_B B FACTORY 5733 5752 5771 5790 5809 5828 5847 5866
vtxtable band 3 BOSCAM_E E FACTORY 5705 5685 5665    0 5885 5905    0    0
vtxtable band 4 FATSHARK F FACTORY 5740 5760 5780 5800 5820 5840 5860 5880
vtxtable band 5 RACEBAND R FACTORY 5658 5695 5732 5769 5806 5843 5880 5917
vtxtable band 6 IMD6     I CUSTOM  5732 5765 5828 5840 5866 5740    0    0
vtxtable powerlevels 4
vtxtable powervalues 25 200 600 800
vtxtable powerlabels 25 200 600 800

# rxfail
rxfail 0 a
rxfail 1 a
rxfail 2 a
rxfail 3 a
rxfail 4 h
rxfail 5 h
rxfail 6 h
rxfail 7 h
rxfail 8 h
rxfail 9 h
rxfail 10 h
rxfail 11 h
rxfail 12 h
rxfail 13 h
rxfail 14 h
rxfail 15 h
rxfail 16 h
rxfail 17 h

# master
set gyro_hardware_lpf = NORMAL
set gyro_sync_denom = 1
set gyro_lowpass_type = PT1
set gyro_lowpass_hz = 200
set gyro_lowpass2_type = PT1
set gyro_lowpass2_hz = 250
set gyro_notch1_hz = 0
set gyro_notch1_cutoff = 0
set gyro_notch2_hz = 0
set gyro_notch2_cutoff = 0
set gyro_calib_duration = 125
set gyro_calib_noise_limit = 48
set gyro_offset_yaw = 0
set gyro_overflow_detect = ALL
set yaw_spin_recovery = ON
set yaw_spin_threshold = 1950
set gyro_to_use = FIRST
set dyn_notch_range = MEDIUM
set dyn_notch_width_percent = 8
set dyn_notch_q = 120
set dyn_notch_min_hz = 150
set dyn_lpf_gyro_min_hz = 200
set dyn_lpf_gyro_max_hz = 500
set gyro_filter_debug_axis = ROLL
set acc_hardware = AUTO
set acc_lpf_hz = 10
set acc_trim_pitch = 0
set acc_trim_roll = 0
set acc_calibration = -6,253,-74
set align_mag = DEFAULT
set mag_align_roll = 0
set mag_align_pitch = 0
set mag_align_yaw = 0
set mag_bustype = I2C
set mag_i2c_device = 1
set mag_i2c_address = 0
set mag_spi_device = 0
set mag_hardware = NONE
set mag_declination = 0
set mag_calibration = 0,0,0
set baro_bustype = I2C
set baro_spi_device = 0
set baro_i2c_device = 1
set baro_i2c_address = 0
set baro_hardware = AUTO
set baro_tab_size = 21
set baro_noise_lpf = 600
set baro_cf_vel = 985
set mid_rc = 1500
set min_check = 1050
set max_check = 1900
set rssi_channel = 0
set rssi_src_frame_errors = OFF
set rssi_scale = 100
set rssi_offset = 0
set rssi_invert = OFF
set rssi_src_frame_lpf_period = 30
set rc_interp = AUTO
set rc_interp_ch = RPYT
set rc_interp_int = 19
set rc_smoothing_type = FILTER
set rc_smoothing_input_hz = 0
set rc_smoothing_derivative_hz = 0
set rc_smoothing_debug_axis = ROLL
set rc_smoothing_input_type = BIQUAD
set rc_smoothing_derivative_type = BIQUAD
set rc_smoothing_auto_smoothness = 10
set fpv_mix_degrees = 0
set max_aux_channels = 14
set serialrx_provider = SBUS
set serialrx_inverted = OFF
set spektrum_sat_bind = 0
set spektrum_sat_bind_autoreset = ON
set srxl2_unit_id = 1
set srxl2_baud_fast = ON
set sbus_baud_fast = OFF
set airmode_start_throttle_percent = 25
set rx_min_usec = 885
set rx_max_usec = 2115
set serialrx_halfduplex = OFF
set adc_device = 1
set adc_vrefint_calibration = 0
set adc_tempsensor_calibration30 = 0
set adc_tempsensor_calibration110 = 0
set input_filtering_mode = OFF
set blackbox_p_ratio = 32
set blackbox_device = SDCARD
set blackbox_record_acc = ON
set blackbox_mode = NORMAL
set min_throttle = 1070
set max_throttle = 2000
set min_command = 1000
set dshot_idle_value = 400
set dshot_burst = ON
set dshot_bidir = OFF
set dshot_bitbang = AUTO
set dshot_bitbang_timer = AUTO
set use_unsynced_pwm = OFF
set motor_pwm_protocol = DSHOT600
set motor_pwm_rate = 480
set motor_pwm_inversion = OFF
set motor_poles = 14
set thr_corr_value = 0
set thr_corr_angle = 800
set failsafe_delay = 3
set failsafe_off_delay = 10
set failsafe_throttle = 1000
set failsafe_switch_mode = STAGE1
set failsafe_throttle_low_delay = 100
set failsafe_procedure = DROP
set failsafe_recovery_delay = 20
set failsafe_stick_threshold = 30
set align_board_roll = 0
set align_board_pitch = 0
set align_board_yaw = 0
set gimbal_mode = NORMAL
set bat_capacity = 0
set vbat_max_cell_voltage = 430
set vbat_full_cell_voltage = 410
set vbat_min_cell_voltage = 330
set vbat_warning_cell_voltage = 350
set vbat_hysteresis = 1
set current_meter = NONE
set battery_meter = ADC
set vbat_detect_cell_voltage = 300
set use_vbat_alerts = ON
set use_cbat_alerts = OFF
set cbat_alert_percent = 10
set vbat_cutoff_percent = 100
set force_battery_cell_count = 0
set vbat_lpf_period = 30
set ibat_lpf_period = 10
set vbat_duration_for_warning = 0
set vbat_duration_for_critical = 0
set vbat_scale = 110
set vbat_divider = 10
set vbat_multiplier = 1
set ibata_scale = 179
set ibata_offset = 0
set ibatv_scale = 0
set ibatv_offset = 0
set beeper_inversion = ON
set beeper_od = OFF
set beeper_frequency = 0
set beeper_dshot_beacon_tone = 1
set yaw_motors_reversed = OFF
set crashflip_motor_percent = 0
set 3d_deadband_low = 1406
set 3d_deadband_high = 1514
set 3d_neutral = 1460
set 3d_deadband_throttle = 50
set 3d_limit_low = 1000
set 3d_limit_high = 2000
set 3d_switched_mode = OFF
set servo_center_pulse = 1500
set servo_pwm_rate = 50
set servo_lowpass_hz = 0
set tri_unarmed_servo = ON
set channel_forwarding_start = 4
set reboot_character = 82
set serial_update_rate_hz = 100
set imu_dcm_kp = 2500
set imu_dcm_ki = 0
set small_angle = 180
set auto_disarm_delay = 5
set gyro_cal_on_first_arm = OFF
set gps_provider = UBLOX
set gps_sbas_mode = AUTO
set gps_auto_config = ON
set gps_auto_baud = OFF
set gps_ublox_use_galileo = OFF
set gps_set_home_point_once = OFF
set gps_use_3d_speed = OFF
set gps_rescue_angle = 25
set gps_rescue_initial_alt = 50
set gps_rescue_descent_dist = 50
set gps_rescue_landing_alt = 5
set gps_rescue_landing_dist = 10
set gps_rescue_ground_speed = 1500
set gps_rescue_throttle_p = 150
set gps_rescue_throttle_i = 20
set gps_rescue_throttle_d = 50
set gps_rescue_velocity_p = 80
set gps_rescue_velocity_i = 20
set gps_rescue_velocity_d = 15
set gps_rescue_yaw_p = 40
set gps_rescue_throttle_min = 1199
set gps_rescue_throttle_max = 1600
set gps_rescue_ascend_rate = 500
set gps_rescue_descend_rate = 150
set gps_rescue_throttle_hover = 1280
set gps_rescue_sanity_checks = RESCUE_SANITY_ON
set gps_rescue_min_sats = 5
set gps_rescue_min_dth = 100
set gps_rescue_allow_arming_without_fix = OFF
set gps_rescue_alt_mode = MAX_ALT
set gps_rescue_use_mag = ON
set deadband = 0
set yaw_deadband = 0
set yaw_control_reversed = OFF
set pid_process_denom = 1
set runaway_takeoff_prevention = ON
set runaway_takeoff_deactivate_delay = 500
set runaway_takeoff_deactivate_throttle_percent = 20
set thrust_linear = 0
set transient_throttle_limit = 0
set tlm_inverted = OFF
set tlm_halfduplex = ON
set frsky_default_lat = 0
set frsky_default_long = 0
set frsky_gps_format = 0
set frsky_unit = IMPERIAL
set frsky_vfas_precision = 0
set hott_alarm_int = 5
set pid_in_tlm = OFF
set report_cell_voltage = OFF
set ibus_sensor = 1,2,3,0,0,0,0,0,0,0,0,0,0,0,0
set mavlink_mah_as_heading_divisor = 0
set telemetry_disabled_voltage = OFF
set telemetry_disabled_current = OFF
set telemetry_disabled_fuel = OFF
set telemetry_disabled_mode = OFF
set telemetry_disabled_acc_x = OFF
set telemetry_disabled_acc_y = OFF
set telemetry_disabled_acc_z = OFF
set telemetry_disabled_pitch = OFF
set telemetry_disabled_roll = OFF
set telemetry_disabled_heading = OFF
set telemetry_disabled_altitude = OFF
set telemetry_disabled_vario = OFF
set telemetry_disabled_lat_long = OFF
set telemetry_disabled_ground_speed = OFF
set telemetry_disabled_distance = OFF
set telemetry_disabled_esc_current = ON
set telemetry_disabled_esc_voltage = ON
set telemetry_disabled_esc_rpm = ON
set telemetry_disabled_esc_temperature = ON
set telemetry_disabled_temperature = OFF
set ledstrip_visual_beeper = OFF
set ledstrip_visual_beeper_color = WHITE
set ledstrip_grb_rgb = GRB
set ledstrip_profile = STATUS
set ledstrip_race_color = ORANGE
set ledstrip_beacon_color = WHITE
set ledstrip_beacon_period_ms = 500
set ledstrip_beacon_percent = 50
set ledstrip_beacon_armed_only = OFF
set sdcard_detect_inverted = OFF
set sdcard_mode = SPI
set sdcard_dma = OFF
set sdcard_spi_bus = 3
set osd_units = METRIC
set osd_warn_arming_disable = ON
set osd_warn_batt_not_full = ON
set osd_warn_batt_warning = ON
set osd_warn_batt_critical = ON
set osd_warn_visual_beeper = ON
set osd_warn_crash_flip = ON
set osd_warn_esc_fail = ON
set osd_warn_core_temp = ON
set osd_warn_rc_smoothing = ON
set osd_warn_fail_safe = ON
set osd_warn_launch_control = ON
set osd_warn_no_gps_rescue = ON
set osd_warn_gps_rescue_disabled = ON
set osd_warn_rssi = OFF
set osd_warn_link_quality = OFF
set osd_rssi_alarm = 20
set osd_link_quality_alarm = 80
set osd_rssi_dbm_alarm = 60
set osd_cap_alarm = 2200
set osd_alt_alarm = 100
set osd_esc_temp_alarm = -128
set osd_esc_rpm_alarm = -1
set osd_esc_current_alarm = -1
set osd_core_temp_alarm = 70
set osd_ah_max_pit = 20
set osd_ah_max_rol = 40
set osd_ah_invert = OFF
set osd_tim1 = 2560
set osd_tim2 = 2561
set osd_vbat_pos = 234
set osd_rssi_pos = 2170
set osd_link_quality_pos = 234
set osd_rssi_dbm_pos = 234
set osd_tim_1_pos = 2199
set osd_tim_2_pos = 2103
set osd_remaining_time_estimate_pos = 234
set osd_flymode_pos = 2477
set osd_anti_gravity_pos = 234
set osd_g_force_pos = 234
set osd_throttle_pos = 2489
set osd_vtx_channel_pos = 2049
set osd_crosshairs_pos = 205
set osd_ah_sbar_pos = 206
set osd_ah_pos = 78
set osd_current_pos = 234
set osd_mah_drawn_pos = 234
set osd_motor_diag_pos = 234
set osd_craft_name_pos = 2059
set osd_display_name_pos = 234
set osd_gps_speed_pos = 2456
set osd_gps_lon_pos = 2497
set osd_gps_lat_pos = 2513
set osd_gps_sats_pos = 2137
set osd_home_dir_pos = 2482
set osd_home_dist_pos = 2445
set osd_flight_dist_pos = 2113
set osd_compass_bar_pos = 2091
set osd_altitude_pos = 2081
set osd_pid_roll_pos = 234
set osd_pid_pitch_pos = 234
set osd_pid_yaw_pos = 234
set osd_debug_pos = 234
set osd_power_pos = 234
set osd_pidrate_profile_pos = 234
set osd_warnings_pos = 2378
set osd_avg_cell_voltage_pos = 2465
set osd_pit_ang_pos = 234
set osd_rol_ang_pos = 234
set osd_battery_usage_pos = 234
set osd_disarmed_pos = 2315
set osd_nheading_pos = 234
set osd_nvario_pos = 2433
set osd_esc_tmp_pos = 234
set osd_esc_rpm_pos = 234
set osd_esc_rpm_freq_pos = 234
set osd_rtc_date_time_pos = 234
set osd_adjustment_range_pos = 234
set osd_flip_arrow_pos = 234
set osd_core_temp_pos = 234
set osd_log_status_pos = 234
set osd_stick_overlay_left_pos = 234
set osd_stick_overlay_right_pos = 234
set osd_stick_overlay_radio_mode = 2
set osd_rate_profile_name_pos = 234
set osd_pid_profile_name_pos = 234
set osd_profile_name_pos = 234
set osd_stat_rtc_date_time = OFF
set osd_stat_tim_1 = OFF
set osd_stat_tim_2 = ON
set osd_stat_max_spd = ON
set osd_stat_max_dist = OFF
set osd_stat_min_batt = ON
set osd_stat_endbatt = OFF
set osd_stat_battery = OFF
set osd_stat_min_rssi = ON
set osd_stat_max_curr = ON
set osd_stat_used_mah = ON
set osd_stat_max_alt = OFF
set osd_stat_bbox = ON
set osd_stat_bb_no = ON
set osd_stat_max_g_force = OFF
set osd_stat_max_esc_temp = OFF
set osd_stat_max_esc_rpm = OFF
set osd_stat_min_link_quality = OFF
set osd_stat_flight_dist = OFF
set osd_stat_max_fft = OFF
set osd_stat_total_flights = OFF
set osd_stat_total_time = OFF
set osd_stat_total_dist = OFF
set osd_stat_min_rssi_dbm = OFF
set osd_profile = 1
set osd_profile_1_name = -
set osd_profile_2_name = -
set osd_profile_3_name = -
set osd_gps_sats_show_hdop = OFF
set system_hse_mhz = 8
set task_statistics = ON
set debug_mode = NONE
set rate_6pos_switch = OFF
set cpu_overclock = OFF
set pwr_on_arm_grace = 5
set scheduler_optimize_rate = AUTO
set vtx_band = 4
set vtx_channel = 1
set vtx_power = 4
set vtx_low_power_disarm = OFF
set vtx_freq = 5740
set vtx_pit_mode_freq = 0
set vtx_halfduplex = ON
set vcd_video_system = AUTO
set vcd_h_offset = 0
set vcd_v_offset = 0
set max7456_clock = DEFAULT
set max7456_spi_bus = 2
set max7456_preinit_opu = OFF
set displayport_msp_col_adjust = 0
set displayport_msp_row_adjust = 0
set displayport_max7456_col_adjust = 0
set displayport_max7456_row_adjust = 0
set displayport_max7456_inv = OFF
set displayport_max7456_blk = 0
set displayport_max7456_wht = 2
set esc_sensor_halfduplex = OFF
set esc_sensor_current_offset = 0
set led_inversion = 0
set dashboard_i2c_bus = 1
set dashboard_i2c_addr = 60
set camera_control_mode = HARDWARE_PWM
set camera_control_ref_voltage = 330
set camera_control_key_delay = 180
set camera_control_internal_resistance = 470
set camera_control_button_resistance = 450,270,150,68,0
set camera_control_inverted = OFF
set pinio_config = 1,1,1,1
set pinio_box = 255,255,255,255
set usb_hid_cdc = OFF
set usb_msc_pin_pullup = ON
set flash_spi_bus = 3
set rcdevice_init_dev_attempts = 6
set rcdevice_init_dev_attempt_interval = 1000
set rcdevice_protocol_version = 0
set rcdevice_feature = 0
set gyro_1_bustype = SPI
set gyro_1_spibus = 1
set gyro_1_i2cBus = 0
set gyro_1_i2c_address = 0
set gyro_1_sensor_align = CW270
set gyro_1_align_roll = 0
set gyro_1_align_pitch = 0
set gyro_1_align_yaw = 2700
set gyro_2_bustype = SPI
set gyro_2_spibus = 0
set gyro_2_i2cBus = 0
set gyro_2_i2c_address = 0
set gyro_2_sensor_align = CW0
set gyro_2_align_roll = 0
set gyro_2_align_pitch = 0
set gyro_2_align_yaw = 0
set mco2_on_pc9 = OFF
set timezone_offset_minutes = 0
set gyro_rpm_notch_harmonics = 3
set gyro_rpm_notch_q = 500
set gyro_rpm_notch_min = 100
set dterm_rpm_notch_harmonics = 0
set dterm_rpm_notch_q = 500
set dterm_rpm_notch_min = 100
set rpm_notch_lpf = 150
set stats = OFF
set stats_total_flights = 0
set stats_total_time_s = 0
set stats_total_dist_m = 0
set name = Darwin129
set display_name = -
set position_alt_source = DEFAULT

profile 0

# profile 0
set profile_name = -
set dyn_lpf_dterm_min_hz = 70
set dyn_lpf_dterm_max_hz = 170
set dterm_lowpass_type = PT1
set dterm_lowpass_hz = 150
set dterm_lowpass2_type = PT1
set dterm_lowpass2_hz = 150
set dterm_notch_hz = 0
set dterm_notch_cutoff = 0
set vbat_pid_gain = OFF
set pid_at_min_throttle = ON
set anti_gravity_mode = SMOOTH
set anti_gravity_threshold = 250
set anti_gravity_gain = 5000
set feedforward_transition = 0
set acc_limit_yaw = 0
set acc_limit = 0
set crash_dthreshold = 50
set crash_gthreshold = 400
set crash_setpoint_threshold = 350
set crash_time = 500
set crash_delay = 0
set crash_recovery_angle = 10
set crash_recovery_rate = 100
set crash_limit_yaw = 200
set crash_recovery = OFF
set iterm_rotation = OFF
set iterm_relax = RP
set iterm_relax_type = SETPOINT
set iterm_relax_cutoff = 20
set iterm_windup = 100
set iterm_limit = 400
set pidsum_limit = 500
set pidsum_limit_yaw = 400
set yaw_lowpass_hz = 0
set throttle_boost = 5
set throttle_boost_cutoff = 15
set acro_trainer_angle_limit = 20
set acro_trainer_lookahead_ms = 50
set acro_trainer_debug_axis = ROLL
set acro_trainer_gain = 75
set p_pitch = 66
set i_pitch = 117
set d_pitch = 65
set f_pitch = 137
set p_roll = 60
set i_roll = 111
set d_roll = 60
set f_roll = 129
set p_yaw = 43
set i_yaw = 117
set d_yaw = 0
set f_yaw = 129
set angle_level_strength = 50
set horizon_level_strength = 50
set horizon_transition = 75
set level_limit = 55
set horizon_tilt_effect = 75
set horizon_tilt_expert_mode = OFF
set abs_control_gain = 0
set abs_control_limit = 90
set abs_control_error_limit = 20
set abs_control_cutoff = 11
set use_integrated_yaw = OFF
set integrated_yaw_relax = 200
set d_min_roll = 34
set d_min_pitch = 38
set d_min_yaw = 0
set d_min_boost_gain = 27
set d_min_advance = 20
set motor_output_limit = 100
set auto_profile_cell_count = 0
set launch_control_mode = NORMAL
set launch_trigger_allow_reset = ON
set launch_trigger_throttle_percent = 20
set launch_angle_limit = 0
set launch_control_gain = 40
set ff_interpolate_sp = AVERAGED
set ff_spike_limit = 60
set ff_max_rate_limit = 100
set ff_boost = 15
set idle_min_rpm = 0
set idle_adjustment_speed = 50
set idle_p = 50
set idle_pid_limit = 200
set idle_max_increase = 150

rateprofile 0

# rateprofile 0
set rateprofile_name = -
set thr_mid = 50
set thr_expo = 0
set rates_type = BETAFLIGHT
set roll_rc_rate = 100
set pitch_rc_rate = 100
set yaw_rc_rate = 100
set roll_expo = 0
set pitch_expo = 0
set yaw_expo = 0
set roll_srate = 70
set pitch_srate = 70
set yaw_srate = 70
set tpa_rate = 65
set tpa_breakpoint = 1250
set tpa_mode = D
set throttle_limit_type = OFF
set throttle_limit_percent = 100
set roll_rate_limit = 1998
set pitch_rate_limit = 1998
set yaw_rate_limit = 1998

# end the command batch
batch end

# 
save
