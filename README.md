# Thistle Demo

### Instructions:
Need to update `arduino_i2c` parameter:

```
arduino_i2c: &i2c0 {
	status = "okay";
	clock-frequency = <I2C_BITRATE_STANDARD>;
	sda-gpios = <&gpio0 21 GPIO_OPEN_DRAIN>;
	scl-gpios = <&gpio0 22 GPIO_OPEN_DRAIN>;
	pinctrl-0 = <&i2c0_default>;
	pinctrl-names = "default";
};
```
