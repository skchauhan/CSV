# CSV

if (($handle = fopen(CSV_UPLOAD_PATH.$strProfileName, "r")) !== FALSE) {

    while (($data = fgetcsv($handle, 0, ",")) !== FALSE) {
    
        print_r($data);
        
    }
    
}
