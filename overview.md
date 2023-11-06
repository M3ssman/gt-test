<link rel="stylesheet" href="table_hide.css"/>
<link rel="stylesheet"
      type="text/css"
      href="https://cdn.datatables.net/1.11.4/css/jquery.dataTables.css"/>
<script type="text/javascript"
        charset="utf8"
        src="https://code.jquery.com/jquery-3.5.1.js"> </script>
<script charset="utf8"
        type="text/javascript"
        src="https://cdn.datatables.net/1.11.4/js/jquery.dataTables.min.js"> </script>
<script type="text/javascript">
                    $(document).ready(function() {
                    $('#table_id').DataTable( {
                    "scrollX": "1800px",
                    "scrollCollapse": true,
                    "pagingType": "full_numbers",
                    "ordering": true,
                    "info":     true,
                    
                    } );
                    } );
                </script>
<div>
   <h2>Details</h2>
   <ul>
      <li>
         <a href="metadata">Metadata</a>
      </li>
      <li>
         <a href="table">Compressed table view</a>
      </li>
   </ul>
</div>
<h2>Detailed table view</h2>
<div>
   <table class="noStyle">
      <tr>
         <td>
            <details>
               <summary>Legend</summary>
               <dl class="grid_only">
                  <dt>TextLine</dt>
                  <dd>TextLine</dd>
                  <dt>Page</dt>
                  <dd>Page</dd>
                  <dt>TxtRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lytextregion.html"
                        target="_blank">TextRegion</a>
                  </dd>
                  <dt>ImgRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyBildbereiche.html"
                        target="_blank">ImageRegion</a>
                  </dd>
                  <dt>LineDrawRegion</dt>
                  <dd>LineDrawingRegion</dd>
                  <dt>GraphRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyGraphik.html"
                        target="_blank">GraphicRegion</a>
                  </dd>
                  <dt>TabRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyTabellen.html"
                        target="_blank">TableRegion</a>
                  </dd>
                  <dt>ChartRegion</dt>
                  <dd>ChartRegion</dd>
                  <dt>SepRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lySeparatoren.html"
                        target="_blank">SeperatorRegion</a>
                  </dd>
                  <dt>MathRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyMathematische_Zeichen.html"
                        target="_blank">MathsRegion</a>
                  </dd>
                  <dt>ChemRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyChemische_Symbole.html"
                        target="_blank">ChemRegion</a>
                  </dd>
                  <dt>MusicRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyNotenzeichen.html"
                        target="_blank">MusicRegion</a>
                  </dd>
                  <dt>AdRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyWerbung.html"
                        target="_blank">AdvertRegion</a>
                  </dd>
                  <dt>NoiseRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lyRauschen.html"
                        target="_blank">NoiseRegion</a>
                  </dd>
                  <dt>UnkownRegion</dt>
                  <dd>
                     <a href="https://ocr-d.de/de/gt-guidelines/trans/lySonstiges.html"
                        target="_blank">UnkownRegion</a>
                  </dd>
                  <dt>CustomRegion</dt>
                  <dd>CustomRegion</dd>
               </dl>
            </details>
         </td>
      </tr>
   </table>
</div>
<table id="table_id">
   <thead>
      <tr>
         <th style="position: sticky !important; left: 0 !important;">document</th>
         <th>TxtRegion</th>
         <th>ImgRegion</th>
         <th>LineDrawRegion</th>
         <th>GraphRegion</th>
         <th>TabRegion</th>
         <th>ChartRegion</th>
         <th>SepRegion</th>
         <th>MathRegion</th>
         <th>ChemRegion</th>
         <th>MusicRegion</th>
         <th>AdRegion</th>
         <th>NoiseRegion</th>
         <th>UnkownRegion</th>
         <th>CustomRegion</th>
         <th>TextLine</th>
         <th>Page</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <th>urn+nbn+de+gbv+3+1-842201-p0538-0_lat.gt.xml</th>
         <td>4</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>27</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-770985-p0152-7_lat.gt.xml</th>
         <td>6</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>1</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>39</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-703538-p0544-6_lat.gt.xml</th>
         <td>3</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>34</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-331894-p0412-6_lat.gt.xml</th>
         <td>1</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>29</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-428479-p0029-8_lat.gt.xml</th>
         <td>7</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>39</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-799224-p0090-7_lat.gt.xml</th>
         <td>5</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>57</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-757909-p0542-9_lat.gt.xml</th>
         <td>8</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>43</td>
         <td>1</td>
      </tr>
      <tr>
         <th>urn+nbn+de+gbv+3+1-806751-p0354-4_lat.gt.xml</th>
         <td>9</td>
         <td>0</td>
         <td>0</td>
         <td>1</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>0</td>
         <td>34</td>
         <td>1</td>
      </tr>
   </tbody>
</table>
