# Read & Reset Maintenance Indicating Light (MIL), aka Check Engine Light (CEL)

**Before STARTING the NT, verify the MIL light has cleared after the short self-check. If the MIL stays on after the short self check, don't start the NT or cycle the ignition switch to clear the MIL.**

If the MIL is present after the short self-check before starting the engine, read the MIL code by:
- shifting to neutral
- release clutch
- lower kickstand
Read MIL flashes. Long is ~1.3 seconds & counts as 10. Short is .5 second & counts as 1. If there is more than one code, it should blink one code then the next in numerical order (not chronological order), then it continues to repeat flashing the codes.

If the MIL clears as normal after the self check, but the NT is hard to start & no MIL as come on, crank to start for >10 seconds & a MIL should come on. Then while the MIL is on, do the above to read the MIL flash codes.

If you notice a MIL when riding, pull over and don't turn engine off. If the engine dies because of the MIL, don't turn the ignition off. Read the MIL flash codes by performing the following steps.
- shifting to neutral
- release clutch
- lower kickstand
Read MIL flashes. Long is ~1.3 seconds & counts as 10. Short is .5 second & counts as 1. If there is more than one code, it should blink one code then the next in numerical order (not chronological order), then it continues to repeat flashing the codes.

## How to read MIL codes stored in ECM.
If you see a MIL, the code for MIL will also be stored in your ECM even if the MIL has since cleared. If you want to read the fault for a previous event when the MIL was on but it has since cleared, do this:
- Ignition switch off
- Remove seat and left side cover.
- Remove the red cap off of the Dummy Load Connector (DLC). It's the 4 wire connector with the red cap just forward of the ECM (main computer card).
- Insert a shorting wire into the Brown and Green wire's terminals of the DLC. I use a ~4" long speaker wire. Any small wire should work. Don't jam a big wire in there.
- Verify engine kill switch is ON.
- Turn Ignition switch ON
- Read blink codes on MIL
If there is more than one code, it should blink one code then the next in numerical order (not chronological order), then it continues to repeat flashing the codes.
- Turn ignition switch off, remove shorting wire, replace cap & side cover & seat.

## How to clear the codes in the ECM.
The ECM doesn't save the previous fault codes in chronological order. Because of that, it is a good idea to clear the codes & keep the register empty so that in an event of a new MIL fault code occurring there won't be other codes stored in the ECM to confuse any future troubleshooting. If you are concerned about having proof of past codes (ie ...to show a shop) I would suggest videoing your old codes flashing. To clear the codes:
- Ignition switch off
- Remove seat and left side cover.
- Remove the red cap off of the Dummy Load Connector (DLC). It's the 4 wire connector with the red cap just forward of the ECM (main computer card).
- Insert a shorting wire into the Brown and Green wire's terminals of the DLC. I use a ~4" long speaker wire. Any small wire should work.
- Verify engine kill switch is ON.
- Turn Ignition switch to ON.
- Temporarily remove the shorting wire in the DLC plug. The MIL will have a solid yellow light for 5 seconds, reinsert the shorting wire into same Brown/Green wire terminals on the DLC during the 5 seconds.
- Verify MIL goes OFF, then starts blinking. The ECM memory is now cleared. If you're unsure that the codes were cleared try reading the stored codes in the ECM from steps above.
- Turn ignition switch off, remove shorting wire, replace cap & side cover & seat.

## MIL blink codes for the NT
1 MAP (Manifold Air Pressure) Sensor Voltage high or low
2 MAP Sensor performance problem
7 ECT (Engine Coolant Temperature) Sensor voltage high or low
8 TP (Throttle Position) Sensor voltage high or low
9 IAT (Inlet Air Temperature) Sensor voltage high or low
11 VS (Vehicle Speed) sensor lost
12 #1 injector malfunction. Will not start.
13 #2 injector malfunction. Will not start.
18 CMP (Cam Position) sensor lost. Will not start.
19 CKP (Crank Position) sensor lost. Will not start.
21 O2 sensor malfunction
23 O2 sensor heater malfunction
29 IACV (Idle Air Control Valve) malfunction (Engine stalls/ hard to start/ rough idle.... Faulty idle speed control valve.)
32 Engine runs normally - Faulty ECM EEPROM

