```<h:panelGroup rendered="#{not empty track.destinationCoordinates}">
                            <p:gmap center="#{track.destinationCoordinates}" fitBounds="true" zoom="2" model="#{track.mapModel}" type="PLAN"  style="width:620px;height:360px;">
                                <p:ajax event="pointSelect" listener="#{track.onPointSelect}"/>
                            </p:gmap>

                </h:panelGroup>
                        
                        private String destinationCoordinates;```