Condition icon packs support
add activity with action "org.omnirom.BatteryIconPack"
the name is used to defined the prefix for the image names
real image name will be
<name>_<percent>
<name>_charge_<percent>
```xml
        <activity
            android:name=".stat_sys_battery_square"
            android:label="Square" >
            <intent-filter>
                <action android:name="org.omnirom.BatteryIconPack" />

                <category android:name="android.intent.category.DEFAULT" />
            </intent-filter>
        </activity>
```
