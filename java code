package com.example.android.elclassico;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {
    int barcaGoal = 0;
    int realGoal = 0;
    int realFouls = 0 ;
    int barcaFouls = 0 ;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

    public void barcaGoals(View v) {
        barcaGoal = barcaGoal + 1;
        display(barcaGoal);

    }

    private void display(int medo) {
        TextView medoView = (TextView) findViewById(R.id.score1);
        medoView.setText(String.valueOf(medo));

    }
    public void foulsDisplay(View v) {
        barcaFouls = barcaFouls + 1;
        display2(barcaFouls);
    }

    private void display2(int medo) {
        TextView medoView = (TextView) findViewById(R.id.fouls1);
        medoView.setText(String.valueOf(medo));
    }

public void realDisplay ( View v ){
    realGoal = realGoal +1 ;
    display3(realGoal);
}
private void display3 (int medo){
        TextView medoView = (TextView)findViewById(R.id.realScore);
        medoView.setText(String.valueOf(medo));
}
public void foulsReal (View v ){
        realFouls = realFouls + 1 ;
        display4(realFouls);
}
public void display4 (int medo){
        TextView medoView = (TextView)findViewById(R.id.realFoul);
        medoView.setText(String.valueOf(medo));
}
public void rest (View v ){
    int barcaGoal = 0;
    int realGoal = 0;
    int realFouls = 0 ;
    int barcaFouls = 0 ;

    display(barcaGoal);
    display2(barcaFouls);
    display3(realGoal);
    display4(realFouls);

}
}

