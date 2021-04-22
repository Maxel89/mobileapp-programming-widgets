
# Rapport

Jag skapade tre objekt enligt instruktioner en ImageView som jag förstorade samt gav en marginal på 20dp (se kodexempel nedan), samt två TextViews som jag ändrade storleken på och satte gravitationen till center_horizontal för att få texten centrerad.
För att få allt centrerat till mitten av skärmen skpade jag två nästlade LinearLayout och satte deras gravitation till center. 

        <ImageView
            android:id="@+id/imageView"
            android:layout_width="212dp"
            android:layout_height="188dp"
            app:srcCompat="@android:drawable/btn_star_big_on"
            android:layout_marginBottom="20dp"
            />
            
                    <TextView
            android:text="Hello"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:id="@+id/textView1"
            android:layout_gravity="center_horizontal"
            android:textSize="40sp"/>
