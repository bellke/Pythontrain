# Pythontrain

#Remove NaN/NULL columns in a Pandas dataframe?

df=df.dropna(axis=1,how='all')

#Conditional Mean

highestqual = df['quality'] == 9
The_highest_quality_wine_has_an_avg_alcohol_volume_of = df.loc[highestqual, 'alcohol'].mean()
