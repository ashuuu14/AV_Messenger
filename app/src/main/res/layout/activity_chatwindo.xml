<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/chatback"
    tools:context=".chatwindo">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:id="@+id/ll1"
        android:gravity="center">

        <de.hdodenhof.circleimageview.CircleImageView
            android:id="@+id/profileimgg"
            android:layout_width="@dimen/_80sdp"
            android:layout_height="@dimen/_80sdp"
            android:src="@drawable/photocamera"
            app:civ_border_color="@color/white"
            android:layout_marginTop="@dimen/_7sdp"
            app:civ_border_width="@dimen/_2sdp"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.226" />

        <TextView
            android:id="@+id/recivername"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="ayushvishwakarma"
            android:gravity="center"
            android:textColor="@color/white"
            android:fontFamily="@font/poppins_regular"
            android:textSize="@dimen/_15sdp"
            android:layout_margin="@dimen/_10sdp"/>
    </LinearLayout>

    <androidx.recyclerview.widget.RecyclerView
        android:id="@+id/msgadpter"
        android:layout_width="match_parent"
        android:layout_height="502dp"
        android:layout_above="@id/ll2"
        android:layout_below="@+id/ll1"
        android:layout_marginTop="7dp"
        android:layout_marginBottom="-7dp"
        android:padding="@dimen/_10sdp" />

    <LinearLayout
        android:id="@+id/ll2"
        android:layout_width="match_parent"
        android:layout_height="@dimen/_45sdp"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="@dimen/_2sdp"
        android:layout_marginTop="@dimen/_2sdp"
        android:layout_marginEnd="@dimen/_2sdp"
        android:layout_marginBottom="@dimen/_2sdp"
        android:orientation="horizontal">

        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="@dimen/_35sdp"
            android:layout_marginStart="@dimen/_4sdp"
            android:layout_marginTop="@dimen/_5sdp"
            android:layout_marginEnd="@dimen/_7sdp"
            android:layout_weight="1"
            app:cardBackgroundColor="@color/white"
            app:cardCornerRadius="@dimen/_25sdp">

            <EditText
                android:id="@+id/textmsg"
                android:layout_width="338dp"
                android:layout_height="45dp"
                android:layout_marginLeft="@dimen/_20sdp"
                android:layout_gravity="center"
                android:background="@null"
                android:fontFamily="@font/poppins_regular"
                android:hint="Type The Messages..."
                android:paddingStart="13.00dp" />

        </androidx.cardview.widget.CardView>

        <androidx.cardview.widget.CardView
            android:id="@+id/sendbtnn"
            android:layout_width="@dimen/_35sdp"
            android:layout_height="@dimen/_35sdp"
            android:layout_marginTop="@dimen/_5sdp"
            android:layout_marginEnd="@dimen/_5sdp"
            app:cardBackgroundColor="@color/white"
            app:cardCornerRadius="@dimen/_25sdp">

            <ImageView
                android:layout_width="@dimen/_15sdp"
                android:layout_height="@dimen/_15sdp"
                android:layout_gravity="center"
                android:background="@drawable/sendbut" />

        </androidx.cardview.widget.CardView>


    </LinearLayout>

</RelativeLayout>