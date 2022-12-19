# NaughtyStringKeyboard


Please help me to create switch button on this script

I've been dizzy to display this section on the keyboard


	
	public static void chooseAKeyboard(@Nullable Context context) {
        if (context != null) {
            InputMethodManager imeManager = (InputMethodManager) context.getSystemService(Context.INPUT_METHOD_SERVICE);
            if (imeManager != null) {
                imeManager.showInputMethodPicker();
            }
        }
	}
	
	public static void switchAKeyboard(@Nullable Context context) {
            InputMethodManager imeManager = (InputMethodManager) context.getSystemService(Settings.ACTION_INPUT_METHOD_SETTINGS);
            if (imeManager != null) {
                imeManager.showInputMethodPicker();
            }
        }
}
