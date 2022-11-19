# Tugas_Mobile
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        android:padding="10dp">

        <LinearLayout
        android:layout_marginBottom="10dp"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="horizontal">

            <ImageView
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:src="@drawable/img_logopdam"/>

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center"
                android:layout_marginLeft="5dp"
                android:fontFamily="@font/didact_gothic"
                android:text="e-PDAM"
                android:textColor="#000000"
                android:textSize="20dp" />

    </LinearLayout>


        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:clickable="true"
            android:foreground="?android:attr/selectableItemBackground"
            app:cardElevation="5dp"
            app:cardCornerRadius="5dp"
            android:layout_margin="5dp"
            android:backgroundTint="@color/colorAccent">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:padding="10dp"
                android:layout_marginHorizontal="20dp">

                <ImageView
                    android:layout_width="80dp"
                    android:layout_height="80dp"
                    android:src="@drawable/img_defaultuser"/>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent">

                <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:orientation="vertical"
                        android:layout_centerInParent="true"
                        android:layout_alignParentLeft="true">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="Adidarma Mahendra"
                    android:textColor="#ffffff"
                    android:fontFamily="@font/didact_gothic"
                    android:textSize="20dp"
                    android:layout_marginLeft="10dp"/>

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="220400"
                    android:textColor="#ffffff"
                    android:fontFamily="@font/didact_gothic"
                    android:textSize="15dp"
                    android:layout_marginLeft="10dp"/>

                </LinearLayout>
                </RelativeLayout>
           </LinearLayout>
        </androidx.cardview.widget.CardView>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Menu Utama"
            android:layout_marginTop="10dp"
            android:layout_marginHorizontal="5dp"
            android:fontFamily="@font/didact_gothic"/>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:weightSum="3"
            android:orientation="horizontal">

            <androidx.cardview.widget.CardView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:foreground="?android:attr/selectableItemBackground"
                android:clickable="true"
                app:cardCornerRadius="10dp"
                app:cardElevation="5dp"
                android:layout_margin="5dp">

                <LinearLayout
                    android:padding="10dp"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="vertical">

                    <ImageView
                        android:layout_width="70dp"
                        android:layout_height="70dp"
                        android:src="@drawable/img_curriculum"
                        android:layout_gravity="center"/>

                    <TextView
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:textAlignment="center"
                        android:textColor="#000000"
                        android:text="Menu 1"/>

                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:foreground="?android:attr/selectableItemBackground"
                android:clickable="true"
                app:cardCornerRadius="10dp"
                app:cardElevation="5dp"
                android:layout_margin="5dp">

                <LinearLayout
                    android:padding="10dp"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="vertical">

                    <ImageView
                        android:layout_width="70dp"
                        android:layout_height="70dp"
                        android:src="@drawable/img_browser"
                        android:layout_gravity="center"/>

                    <TextView
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:textAlignment="center"
                        android:textColor="#000000"
                        android:text="Menu 2"/>

                </LinearLayout>
            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:foreground="?android:attr/selectableItemBackground"
                android:clickable="true"
                app:cardCornerRadius="10dp"
                app:cardElevation="5dp"
                android:layout_margin="5dp">

                <LinearLayout
                    android:padding="10dp"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="vertical">

                    <ImageView
                        android:layout_width="70dp"
                        android:layout_height="70dp"
                        android:src="@drawable/img_smartphone"
                        android:layout_gravity="center"/>

                    <TextView
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:textAlignment="center"
                        android:textColor="#000000"
                        android:text="Menu 3"/>

                </LinearLayout>
            </androidx.cardview.widget.CardView>

        </LinearLayout>
        
        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content">
            
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Log"
                android:fontFamily="@font/didact_gothic"/>

            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Lihat Semua"
                android:layout_alignParentRight="true"
                android:textColor="#03a9F4"/>

        </RelativeLayout>

        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:clickable="true"
            android:foreground="?android:attr/selectableItemBackground"
            app:cardElevation="5dp"
            app:cardCornerRadius="10dp"
            android:layout_margin="5dp">
            
            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">
                
                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="vertical">

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:fontFamily="@font/didact_gothic"
                        android:textSize="20dp"
                        android:textColor="#000000"
                        android:text="Tagihan Bulan Ini"/>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:fontFamily="@font/didact_gothic"
                        android:textSize="20dp"
                        android:textStyle="bold"
                        android:textColor="#000000"
                        android:text="Rp.2.000.000-,"/>
                </LinearLayout>

                <ImageView
                    android:layout_marginRight="10dp"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:src="@drawable/ic_arrow"
                    android:layout_centerInParent="true"
                    android:layout_alignParentRight="true"/>
            </RelativeLayout>
        </androidx.cardview.widget.CardView>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Informasi"
            android:fontFamily="@font/didact_gothic"
            android:layout_marginHorizontal="5dp"/>

        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:clickable="true"
            android:foreground="?android:attr/selectableItemBackground"
            app:cardElevation="5dp"
            app:cardCornerRadius="10dp"
            android:layout_margin="5dp">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="horizontal"
                    android:padding="10dp">

                    <ImageView
                        android:layout_width="70dp"
                        android:layout_height="70dp"
                        android:src="@drawable/img_logopdam"/>
                    
                    <LinearLayout
                        android:layout_marginLeft="10dp"
                        android:layout_width="210dp"
                        android:layout_height="wrap_content"
                        android:orientation="vertical">
                        
                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Website Resmi"
                            android:fontFamily="@font/didact_gothic"
                            android:textColor="#000000"
                            android:textSize="20dp"/>

                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="Dapatkan informasi terupdate dari Perusahaan kami"
                            android:fontFamily="@font/didact_gothic"/>


                    </LinearLayout>

                </LinearLayout>

                <ImageView
                    android:layout_marginRight="10dp"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:src="@drawable/ic_arrow"
                    android:layout_centerInParent="true"
                    android:layout_alignParentRight="true"/>

            </RelativeLayout>

        </androidx.cardview.widget.CardView>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:fontFamily="@font/didact_gothic"
            android:text="Detail"
            android:layout_marginTop="10dp"
            android:layout_marginHorizontal="5dp"/>


            
            

    </LinearLayout>
        </ScrollView>


![image](https://user-images.githubusercontent.com/98471247/202845971-a54e8625-7316-44f6-93ae-97d08be2fe4f.png)
