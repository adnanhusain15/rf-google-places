
        DOCS: https://developers.google.com/maps/documentation/javascript/places#find_place_from_query

        'google' namespace is came from script added to index.html
        1. <script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?key=<YOUR_GOOGLE_API_KEY>&libraries=places"></script>
        2. Installing @types/googlemaps
        3. adding "types": ["googlemaps"] in compilerOptions in tsconfig.json

        fieldProps = {
                onResultClick -> function trigger on clicking result //mandatory field
                suggestionsTypes -> array of suggestion types //mandatory field
        }
