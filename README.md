# Ud2_Ejemplo12
_Ejemplo 12 de la Unidad 2._ 

Vemos la diferencia entre _padding_ y _margin_, para ello sólo hemos de fijarnos en el fichero _activity_main.xml_:

```
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        android:background="@android:color/darker_gray"
        android:paddingLeft="16dp"
        android:paddingRight="16dp"
        android:paddingTop="16dp"
        android:paddingBottom="16dp" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        android:background="@android:color/darker_gray"
        android:layout_marginLeft="16dp"
        android:layout_marginRight="16dp"
        android:layout_marginTop="16dp"
        android:layout_marginBottom="16dp" />

</LinearLayout>
```

Si vamos cambiando sus valores podemos ver su comportamiento.
