# Opisanie2
Описание пехотных юнитов "Терранов": Морпех, Мародер.
![Screenshot](screenshot.png)
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    tools:context=".MainActivity"
    android:orientation="vertical"
    android:background="#555555">


    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="480dp"
        android:background="#555555"
        android:orientation="vertical">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:gravity="center"
            android:text="Морпех"
            android:textColor="#00FF20"
            android:textSize="29sp" />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:gravity="center"
            android:text="Морпехи — первая линия терранской обороны в секторе Копрулу. При Конфедерации большинство морпехов были преступниками или повстанцами, которых подвергали обязательной процедуре невральной ресоциализации, чтобы добиться полной лояльности."
            android:textColor="#00FF20"
            android:textSize="19sp" />
        <ImageView
            android:layout_width="302dp"
            android:layout_height="274dp"
            android:layout_gravity="center"
            android:gravity="center"
            android:src="@drawable/marine" />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:gravity="center"
            android:text="Мародер"
            android:textColor="#00FF20"
            android:textSize="29sp" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:gravity="center"
            android:text="После событий «Войны Выводков» Вооруженным Силам Доминиона было необходимо создать более мощную боевую единицу, способную легко расправляться с панцирем зергов. Чтобы сделать это, было принято решение разработать несколько бронированных костюмов модели СМС-660 на базе огнемётчиков и оснастить их двумя сдвоенными гранатомётами К12 «Каратель». Система авто-погрузки гранат в костюме снабжена всеми компонентами, позволяющими ей собирать и загружать сотни гранат «Каратель». В 2503 году, мародеры вошли в состав Вооруженных Сил Доминиона."
            android:textColor="#00FF20"
            android:textSize="19sp" />

        <ImageView
            android:layout_width="302dp"
            android:layout_height="271dp"
            android:layout_gravity="center"
            android:gravity="center"
            android:src="@drawable/marauder"

            />


        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="#555555"
            android:orientation="horizontal">

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center"
                android:gravity="center"
                android:text="Улучшения"
                android:textColor="#00FF20"
                android:textSize="29sp" />

            <ImageView
                android:layout_width="123dp"
                android:layout_height="118dp"
                android:layout_gravity="center"
                android:gravity="center"
                android:src="@drawable/stim" />

            <ImageView
                android:layout_width="117dp"
                android:layout_height="117dp"
                android:layout_gravity="center"
                android:gravity="center"
                android:src="@drawable/fugasniesnaruadi"/>
            <ImageView
                android:layout_width="117dp"
                android:layout_height="117dp"
                android:layout_gravity="center"
                android:gravity="center"
                android:src="@drawable/shield"/>
        </LinearLayout>





    </LinearLayout>



</ScrollView>




