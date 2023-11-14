# Cupertino Date Picker

Highly customizable cupertino date picker

<img src="https://raw.githubusercontent.com/Dihardja-Software/date-picker-component/master/docs/assets/datepicker.PNG" />

## Usage
```dart
  SizedBox(
    height: 300,
    child: CupertinoDatePicker(
      itemExtent: 50,
      minDate: _minDate,
      maxDate: _maxDate,
      selectedDate: _selectedDate,
      selectionOverlay: Container(
        width: double.infinity,
        height: 50,
        decoration: const BoxDecoration(
          border: Border.symmetric(
            horizontal: BorderSide(color: Colors.grey, width: 1),
          ),
        ),
      ),
      selectedStyle: const TextStyle(
        color: Colors.black,
        fontWeight: FontWeight.w600,
        fontSize: 24,
      ),
      unselectedStyle: TextStyle(
        color: Colors.grey[800],
        fontSize: 18,
      ),
      disabledStyle: TextStyle(
        color: Colors.grey[400],
        fontSize: 18,
      ),
      onSelectedItemChanged: (date) => _selectedDate = date,
    ),
  ),
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
