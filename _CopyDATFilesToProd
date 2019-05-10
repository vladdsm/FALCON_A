# Script to copy DAT files from tester to Files folder of the Terminals
# To be used after training of the robot using Strategy Tester

# files generated in the tester\files folder files copied to the sandbox folder MQL4\Files

# From Terminal 3 to Terminal 1
rsync -r "/Applications/Terminal3.app/Contents/Resources/drive_c/Program Files/FxPro - MetaTrader 4/tester/files/" "/Applications/Terminal1.app/Contents/Resources/drive_c/Program Files/FxPro - MetaTrader 4/MQL4/Files" --include='*.dat' --exclude='*.csv'

# From Terminal 3 to Terminal 3
rsync -r "/Applications/Terminal3.app/Contents/Resources/drive_c/Program Files/FxPro - MetaTrader 4/tester/files/" "/Applications/Terminal3.app/Contents/Resources/drive_c/Program Files/FxPro - MetaTrader 4/MQL4/Files" --include='*.dat' --exclude='*.csv'