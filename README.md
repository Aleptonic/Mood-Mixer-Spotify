
# Mood-Mixer-Spotify

*This is a project on a improved song recommendation system which will  incorporate a 'change-mood' feature which will change the song mood and enhance the music experience*

**Key Technologies:** *Knowledge Graph Indexing, Vector Database*

## Dataset
This is a dataset of Spotify tracks over a range of 125 different genres. Each track has some audio features associated with it. The data is in CSV format which is tabular and can be loaded quickly.

Link for Dataset-> `https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset?resource=download`

### Songs MetaData
- track_id
- artists
- album_name
- track_name
- track_genere
- Various Song features like

        - popularity :(0 to 100; 100 being most popular)
        - duration_ms 
        - explicit :(T/F values)
        - danceability : (0 to 1; 1 being most danceable)
        - energy 
        - key : ( Integers map to pitches using standard Pitch Class notation)
        - loudness : (in dB)
        - mode :(Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0)
        - speachiness
        - acousticness
        - instrumentalness
        - liveness
        - valence :(A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive )
        - tempo : (beats per min)
        - time_signature : (number of beats per bar)
