package com.xarena.remote;

import android.app.Activity;
import android.os.Bundle;
import android.widget.Button;
import android.widget.LinearLayout;
import android.widget.TextView;

public class MainActivity extends Activity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);

        LinearLayout layout = new LinearLayout(this);
        layout.setOrientation(1);
        layout.setPadding(30, 50, 30, 30);

        TextView title = new TextView(this);
        title.setText("XARENA PHONE CONTROL");
        title.setTextSize(24);
        layout.addView(title);

        TextView status = new TextView(this);
        status.setText("Status: Disconnected");
        layout.addView(status);

        Button connect = new Button(this);
        connect.setText("Connect");
        connect.setOnClickListener(v ->
            status.setText("Status: Waiting for permission")
        );
        layout.addView(connect);

        Button disconnect = new Button(this);
        disconnect.setText("Disconnect");
        disconnect.setOnClickListener(v ->
            status.setText("Status: Disconnected")
        );
        layout.addView(disconnect);

        setContentView(layout);
    }
}


پ
