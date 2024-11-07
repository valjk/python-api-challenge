# python-api-challenge
I leveraged Xpert Learning assistant to create the city map using hvplot as I was running into errors due to missing .points at the end of the configuration. I also requested assistance with creating the hover text for the Hotel Map plot.
   
    # Configure the map plot
    city_map = city_data_df.hvplot.points( #Xpert Learning Assistant

    # Configure the map plot
      hotel_map = hotel_df.hvplot.points(
      "Lng",
      "Lat",
      geo=True,
      tiles="OSM",
      size=10,
      color="City",
      cmap="Category20",
      hover_cols=["Hotel Name", "Country"], #Xpert Learning Assistant
      title="Hotel Locations Map",
      )


  
