# Android Features

* Gruppe 1:
* Gruppe 2:
* Gruppe 3:
* Gruppe 4: [Gyroskop and accelerometer](https://github.com/Thug-Lyfe/Gyro-Acc)
  - Marco S. Blum
  - Christian Lind
* Gruppe 5:
* Gruppe 6:
* Gruppe 7:
* Gruppe 8: [Proximity and Database](https://github.com/ElDuderino420/KotlinStuff)
  - David Samuelsen
  - Alexandar Kraunsøe

# Kotlin Features

* Gruppe 1:
* Gruppe 2:
* Gruppe 3:
* Gruppe 4: 
* Gruppe 5:
* Gruppe 6:
* Gruppe 7:
* Gruppe 8: 

# OpenGL

To create an openGL activity, first add the feature to the `AndroidManifest.xml` file:
```xml
<uses-feature
    android:glEsVersion="0x00020000"
    android:required="true" />
```
Create an empty Activity
```kotlin
package dk.cphbusiness.opengles

import android.app.Activity
import android.os.Bundle

class OpenGLActivity : Activity() {
    lateinit var surfaceView: OpenGLSurfaceView

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        surfaceView = OpenGLSurfaceView(this)
        setContentView(surfaceView)
        }

    }
```
