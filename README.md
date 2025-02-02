<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <RadioGroup
        android:id="@+id/radioGroup"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <RadioButton
            android:id="@+id/radioCD"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="CD" />

        <RadioButton
            android:id="@+id/radioLoan"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Loan" />

        <RadioButton
            android:id="@+id/radioChecking"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Checking Account" />
    </RadioGroup>

    <EditText
        android:id="@+id/editTextAccountNumber"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Account Number"
        android:inputType="text" />

    <EditText
        android:id="@+id/editTextInitialBalance"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Initial Balance"
        android:inputType="numberDecimal"
        android:visibility="gone" />

    <EditText
        android:id="@+id/editTextCurrentBalance"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Current Balance"
        android:inputType="numberDecimal" />

    <EditText
        android:id="@+id/editTextInterestRate"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Interest Rate"
        android:inputType="numberDecimal"
        android:visibility="gone" />

    <EditText
        android:id="@+id/editTextPaymentAmount"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Payment Amount"
        android:inputType="numberDecimal"
        android:visibility="gone" />

    <Button
        android:id="@+id/saveButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Save" />

    <Button
        android:id="@+id/cancelButton"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Cancel" />
</LinearLayout>