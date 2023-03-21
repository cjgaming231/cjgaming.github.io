<?xml version="1.0" encoding="utf-8" ?>
<c2project>
    <name>Bad Time Simulator (Sans Fight)</name>
    <description>do you wanna have a bad time? &apos;cause if you visit this page... you are REALLY not going to like what happens next.</description>
    <version>1.0.0.0</version>
    <author>Jcw87</author>
    <author-email></author-email>
    <author-website>http://</author-website>
    <app-id>com.jcw87.badtime</app-id>
    <unique-id>3pln6vqtdnxgu</unique-id>
    <saved-with-version>27500</saved-with-version>
    <used-plugins>
        <plugin author="Scirra" id="AJAX" version="1">AJAX</plugin>
        <plugin author="Scirra" id="Arr" version="1">Array</plugin>
        <plugin author="Scirra" id="Audio" version="1">Audio</plugin>
        <plugin author="Scirra" id="Browser" version="1">Browser</plugin>
        <plugin author="Scirra" id="Dictionary" version="1">Dictionary</plugin>
        <plugin author="Scirra" id="Function" version="1">Function</plugin>
        <plugin author="Scirra" id="Keyboard" version="1">Keyboard</plugin>
        <plugin author="Scirra" id="NinePatch" version="1">9-patch</plugin>
        <plugin author="Scirra" id="Sprite" version="1">Sprite</plugin>
        <plugin author="Scirra" id="Spritefont2" version="1">Sprite font</plugin>
        <plugin author="Scirra" id="TiledBg" version="1">Tiled Background</plugin>
        <plugin author="Scirra" id="Touch" version="1">Touch</plugin>
        <plugin author="Scirra" id="filechooser" version="1">File chooser</plugin>
        <plugin author="Scirra" id="gamepad" version="1">Gamepad</plugin>
    </used-plugins>
    <used-behaviors>
        <behavior author="Scirra" id="custom" version="1">Custom Movement</behavior>
        <behavior author="Scirra" id="jumpthru" version="1">Jump-thru</behavior>
        <behavior author="Scirra" id="solid" version="1">Solid</behavior>
    </used-behaviors>
    <used-effects>
        <effect author="Scirra" id="tint">Tint</effect>
    </used-effects>
    <configurations>
        <configuration exporter-descname="HTML5" exporter-id="html5" name="HTML5" />
    </configurations>
    <window-size>
        <width>640</width>
        <height>480</height>
    </window-size>
    <pixel-rounding>1</pixel-rounding>
    <preview-effects>1</preview-effects>
    <first-layout>MainMenu</first-layout>
    <use-loader-layout>0</use-loader-layout>
    <configuration-settings>
        <prop name="Clear background">Yes</prop>
        <prop name="Downscaling">Low quality</prop>
        <prop name="Enable WebGL">On</prop>
        <prop name="Fullscreen in browser">Letterbox integer scale</prop>
        <prop name="Fullscreen scaling">Low quality</prop>
        <prop name="Loader style">Progress bar &amp; logo</prop>
        <prop name="Orientations">Any</prop>
        <prop name="Pause on unfocus">No</prop>
        <prop name="Physics engine">Box2D asm.js</prop>
        <prop name="Preload sounds">Yes</prop>
        <prop name="Preview browser">Firefox</prop>
        <prop name="Sampling">Point</prop>
        <prop name="Use high-DPI display">Yes</prop>
    </configuration-settings>
    <object-folder>
        <object-folder name="Singletons">
            <object-type name="Gamepad" sid="2737066360312475">
                <plugin id="gamepad" />
            </object-type>
            <object-type name="Keyboard" sid="7004831969366137">
                <plugin id="Keyboard" />
            </object-type>
            <object-type name="VPad" sid="9768267065126338">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="Up" sid="5138796745891601" type="number" />
                    <instance-variable name="Down" sid="8231789435471491" type="number" />
                    <instance-variable name="Left" sid="1260937868110365" type="number" />
                    <instance-variable name="Right" sid="6641724638316461" type="number" />
                    <instance-variable name="Confirm" sid="5899272596289875" type="number" />
                    <instance-variable name="Cancel" sid="4616881591755484" type="number" />
                    <instance-variable name="Menu" sid="2168213636508799" type="number" />
                    <instance-variable name="LastUp" sid="1622459949020876" type="number" />
                    <instance-variable name="LastDown" sid="3653498277383987" type="number" />
                    <instance-variable name="LastLeft" sid="1053485227981488" type="number" />
                    <instance-variable name="LastRight" sid="1751951803115606" type="number" />
                    <instance-variable name="LastConfirm" sid="3632648287625289" type="number" />
                    <instance-variable name="LastCancel" sid="1077614757894582" type="number" />
                    <instance-variable name="LastMenu" sid="9025045177578852" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="6541956784524688" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="Function" sid="7786981344801906">
                <plugin id="Function" />
            </object-type>
            <object-type name="AJAX" sid="1871150019731238">
                <plugin id="AJAX" />
            </object-type>
            <object-type name="Audio" sid="130305442643432">
                <plugin id="Audio" />
            </object-type>
            <object-type name="Touch" sid="833371787328053">
                <plugin id="Touch" />
            </object-type>
        </object-folder>
        <object-folder name="BattleUI">
            <object-type name="HPBackground" sid="8009642851719156">
                <plugin id="TiledBg" />
                <texture />
            </object-type>
            <object-type name="HPBar" sid="5315983389834433">
                <plugin id="TiledBg" />
                <texture />
            </object-type>
            <object-type name="KRBar" sid="8840599197819951">
                <plugin id="TiledBg" />
                <texture />
            </object-type>
            <object-type name="UIAct" sid="9683599283524679">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="7839461660390996" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Highlight" pingpong="0" repeatcount="1" repeatto="0" sid="5181432374441549" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_actbt_center_1.png">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="UIFight" sid="9343233059165768">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="2415236592226629" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Highlight" pingpong="0" repeatcount="1" repeatto="0" sid="5506998997872373" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_fightbt_1.png">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="UIItem" sid="9790445263738264">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="4560456212490265" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Highlight" pingpong="0" repeatcount="1" repeatto="0" sid="7286896709592169" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_itembt_1.png">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="UIMercy" sid="3900276529955833">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="5127942938396299" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Highlight" pingpong="0" repeatcount="1" repeatto="0" sid="4270938902148832" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0">
                            <image-point name="Heart" x="0.145455" y="0.5" />
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="CombatZone" sid="141231765387603">
                <plugin id="NinePatch" />
                <instance-variables>
                    <instance-variable name="TargetLeft" sid="6021697186517032" type="number" />
                    <instance-variable name="TargetTop" sid="7358547809624895" type="number" />
                    <instance-variable name="TargetRight" sid="1387227575863189" type="number" />
                    <instance-variable name="TargetBottom" sid="9275911755738286" type="number" />
                    <instance-variable name="InfoText" sid="9266371524172021" type="string" />
                </instance-variables>
                <texture />
            </object-type>
            <object-type name="CombatZoneBorder" sid="6657741784745805">
                <plugin id="TiledBg" />
                <behaviors>
                    <behavior-type name="Solid" sid="986637488598136">
                        <behavior id="solid" />
                    </behavior-type>
                </behaviors>
                <texture />
            </object-type>
            <object-type name="CombatZoneClipper" sid="2903163662070948">
                <plugin id="TiledBg" />
                <texture />
            </object-type>
            <object-type name="Target" sid="4243712716812677">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="State" sid="5475329447475825" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="698907272053593" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0.504274" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_target_0.png">
                            <collision-poly>
                                <point x="0.0693431" y="0.324786" />
                                <point x="0.5" y="0.00854701" />
                                <point x="0.930657" y="0.324786" />
                                <point x="0.998175" y="0.495726" />
                                <point x="0.928832" y="0.666667" />
                                <point x="0.5" y="0.982906" />
                                <point x="0.0711679" y="0.666667" />
                                <point x="0.00182482" y="0.495726" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="HP" sid="1931015301211759">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="8343756916975768" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="1" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_hpname_0.png">
                            <collision-poly>
                                <point x="0" y="0" />
                                <point x="0.956522" y="0.1" />
                                <point x="0.956522" y="0.5" />
                                <point x="0.826087" y="0.6" />
                                <point x="0" y="1" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="KR" sid="2609083740733856">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="4658499880468184" speed="5">
                        <frame duration="1" hotspotX="1" hotspotY="1" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_krmeter_0.png" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="TargetChoice" sid="260070398441684">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="Direction" sid="6124536967285148" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="2" loop="1" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="6300494068884098" speed="30">
                        <frame duration="3" hotspotX="0.5" hotspotY="0.5" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_targetchoice_0.png" />
                        <frame duration="2" hotspotX="0.5" hotspotY="0.5" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_targetchoice_1.png" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="Strike" sid="1284677255483501">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="6" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="942583768887371" speed="10">
                        <frame duration="1" hotspotX="-1" hotspotY="5.66667" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_strike_0.png">
                            <collision-poly>
                                <point x="0.5" y="0" />
                                <point x="1" y="0" />
                                <point x="0.5" y="0.5" />
                                <point x="0.5" y="0.666667" />
                                <point x="0.5" y="0.333333" />
                                <point x="0" y="1" />
                                <point x="0" y="0.5" />
                            </collision-poly>
                        </frame>
                        <frame duration="1" hotspotX="-0.5" hotspotY="1.36364" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_strike_1.png" />
                        <frame duration="1" hotspotX="0" hotspotY="0.428571" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_strike_2.png" />
                        <frame duration="1" hotspotX="0" hotspotY="0.15625" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_strike_3.png" />
                        <frame duration="1" hotspotX="0" hotspotY="-0.75" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_strike_4.png" />
                        <frame duration="1" hotspotX="-0.142857" hotspotY="-4" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_strike_5.png" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="CombatZoneUnclipper" sid="2731133994133496">
                <plugin id="TiledBg" />
                <texture />
            </object-type>
        </object-folder>
        <object-folder name="Enemies">
            <object-type name="SansHead" sid="2086066613273419">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="T" sid="1558614189746918" type="number" />
                    <instance-variable name="OffsetX" sid="4074126684641977" type="number" />
                    <instance-variable name="OffsetY" sid="8283317758694072" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="2276838282479599" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="LookLeft" pingpong="0" repeatcount="1" repeatto="0" sid="4388466239935075" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Wink" pingpong="0" repeatcount="1" repeatto="0" sid="6457042623121455" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="ClosedEyes" pingpong="0" repeatcount="1" repeatto="0" sid="8089043188246127" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="NoEyes" pingpong="0" repeatcount="1" repeatto="0" sid="2373656401037775" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="2" loop="0" name="BlueEye" pingpong="0" repeatcount="1" repeatto="0" sid="4492125680738175" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Sweat" x="0.5" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Tired1" pingpong="0" repeatcount="1" repeatto="0" sid="9055351961421601" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_sansb_face_2.png">
                            <image-point name="Sweat" x="0.5" y="0" />
                            <collision-poly>
                                <point x="0.125" y="0.133333" />
                                <point x="0.5" y="0" />
                                <point x="0.875" y="0.133333" />
                                <point x="0.96875" y="0.5" />
                                <point x="0.875" y="0.866667" />
                                <point x="0.5" y="1" />
                                <point x="0.125" y="0.866667" />
                                <point x="0.03125" y="0.5" />
                            </collision-poly>
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Tired2" pingpong="0" repeatcount="1" repeatto="0" sid="3836599280297155" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_sansb_face_9.png">
                            <image-point name="Sweat" x="0.5" y="0" />
                            <collision-poly>
                                <point x="0.125" y="0.133333" />
                                <point x="0.5" y="0" />
                                <point x="0.875" y="0.133333" />
                                <point x="0.96875" y="0.5" />
                                <point x="0.875" y="0.866667" />
                                <point x="0.5" y="1" />
                                <point x="0.125" y="0.866667" />
                                <point x="0.03125" y="0.5" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="SansBody" sid="6007327897630886">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="4" loop="0" name="HandDown" pingpong="0" repeatcount="1" repeatto="0" sid="6043785673298376" speed="15">
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.4" />
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.385714" />
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.428571" />
                            <collision-poly>
                                <point x="0" y="0" />
                                <point x="0.984375" y="0" />
                                <point x="0.984375" y="1" />
                                <point x="0" y="1" />
                            </collision-poly>
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.442857" />
                        </frame>
                    </animation>
                    <animation framecount="5" loop="0" name="HandUp" pingpong="0" repeatcount="1" repeatto="0" sid="6693843986666905" speed="15">
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.428571" />
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.442857" />
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.4" />
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.385714" />
                        </frame>
                        <frame duration="1" hotspotX="0.46875" hotspotY="1">
                            <image-point name="Head" x="0.46875" y="0.4" />
                        </frame>
                    </animation>
                    <animation framecount="5" loop="0" name="HandRight" pingpong="0" repeatcount="1" repeatto="0" sid="2519219101455278" speed="15">
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.34375" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.322917" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.3125" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.375" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.354167" y="0.125" />
                        </frame>
                    </animation>
                    <animation framecount="5" loop="0" name="HandLeft" pingpong="0" repeatcount="1" repeatto="0" sid="1931647922176485" speed="15">
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.354167" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.375" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.3125" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.322917" y="0.125" />
                        </frame>
                        <frame duration="1" hotspotX="0.34375" hotspotY="1">
                            <image-point name="Head" x="0.34375" y="0.125" />
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="SansLegs" sid="9590658027348857">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="NextAttack" sid="2281878023018379" type="number" />
                    <instance-variable name="HitAttempts" sid="900119164280441" type="number" />
                    <instance-variable name="DodgeState" sid="5098251647105319" type="number" />
                    <instance-variable name="DodgeTimer" sid="3509506029893432" type="number" />
                    <instance-variable name="JustDodged" sid="7696753463127348" type="boolean" />
                    <instance-variable name="XSpeed" sid="4058871107931012" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Standing" pingpong="0" repeatcount="1" repeatto="0" sid="5481948914165362" speed="5">
                        <frame duration="1" hotspotX="0.477273" hotspotY="1">
                            <image-point name="Torso" x="0.477273" y="0" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Sitting" pingpong="0" repeatcount="1" repeatto="0" sid="6382436399145165" speed="5">
                        <frame duration="1" hotspotX="0.480769" hotspotY="0.882353">
                            <image-point name="Torso" x="0.480769" y="0.0588235" />
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="SansSweat" sid="4934231145646729">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Sweat1" pingpong="0" repeatcount="1" repeatto="0" sid="7107173151154428" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0" />
                    </animation>
                    <animation framecount="1" loop="0" name="Sweat2" pingpong="0" repeatcount="1" repeatto="0" sid="2389381723178476" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0" />
                    </animation>
                    <animation framecount="1" loop="0" name="Sweat3" pingpong="0" repeatcount="1" repeatto="0" sid="2164871598142847" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="SansTorso" sid="6308750117528714">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="T" sid="3683915590450527" type="number" />
                    <instance-variable name="OffsetX" sid="7388070819070914" type="number" />
                    <instance-variable name="OffsetY" sid="6179632542687228" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="1874766620274337" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1">
                            <image-point name="Head" x="0.5" y="0.24" />
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="Shrug" pingpong="0" repeatcount="1" repeatto="0" sid="1031353307450106" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="1" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_sansb_torso_1.png">
                            <image-point name="Head" x="0.5" y="0.208333" />
                            <collision-poly>
                                <point x="0" y="0" />
                                <point x="0.5" y="0.166667" />
                                <point x="1" y="0" />
                                <point x="0.986111" y="0.958333" />
                                <point x="0.0138889" y="0.958333" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="SpeechBubble" sid="4418147656760408">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="4563758704400881" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_blconwdshrt_0.png">
                            <collision-poly>
                                <point x="0.105485" y="0.240385" />
                                <point x="0.49789" y="0" />
                                <point x="0.970464" y="0.0673077" />
                                <point x="1" y="0.5" />
                                <point x="0.974684" y="0.942308" />
                                <point x="0.49789" y="1" />
                                <point x="0.105485" y="0.759615" />
                            </collision-poly>
                        </frame>
                    </animation>
                    <animation framecount="1" loop="0" name="NoEffects" pingpong="0" repeatcount="1" repeatto="0" sid="4566612407065255" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0">
                            <collision-poly>
                                <point x="0.105485" y="0.240385" />
                                <point x="0.49789" y="0" />
                                <point x="0.970464" y="0.0673077" />
                                <point x="1" y="0.5" />
                                <point x="0.974684" y="0.942308" />
                                <point x="0.49789" y="1" />
                                <point x="0.105485" y="0.759615" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
        </object-folder>
        <object-folder name="Attacks">
            <object-type name="BoneH" sid="3019589746608161">
                <plugin id="NinePatch" />
                <texture />
            </object-type>
            <object-type name="BoneV" sid="3868174782291034">
                <plugin id="NinePatch" />
                <texture />
            </object-type>
            <object-type name="GasterBlast1" sid="9836012384209519">
                <plugin id="TiledBg" />
                <instance-variables>
                    <instance-variable name="BlastTime" sid="9838422767648153" type="number" />
                    <instance-variable name="Timer" sid="3111458825166214" type="number" />
                    <instance-variable name="BaseSize" sid="4499117244240895" type="number" />
                    <instance-variable name="SineSize" sid="3652599263413905" type="number" />
                </instance-variables>
                <container>
                    <type>GasterBlaster</type>
                    <type>GasterBlastHit</type>
                    <type>GasterBlast1</type>
                    <type>GasterBlast2</type>
                    <type>GasterBlast3</type>
                </container>
                <texture />
            </object-type>
            <object-type name="GasterBlaster" sid="7974524067202295">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="Ang" sid="3339694860544266" type="number" />
                    <instance-variable name="EndX" sid="5496271542375511" type="number" />
                    <instance-variable name="EndY" sid="6947181727264729" type="number" />
                    <instance-variable name="EndAng" sid="9692461505937431" type="number" />
                    <instance-variable name="State" sid="8667025344021268" type="number" />
                    <instance-variable name="Timer" sid="4004809633270347" type="number" />
                    <instance-variable name="LeaveSpeed" sid="1374973730100997" type="number" />
                </instance-variables>
                <container>
                    <type>GasterBlaster</type>
                    <type>GasterBlastHit</type>
                    <type>GasterBlast1</type>
                    <type>GasterBlast2</type>
                    <type>GasterBlast3</type>
                </container>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="140797437682819" speed="5">
                        <frame duration="1" hotspotX="0.491228" hotspotY="0.5">
                            <collision-poly>
                                <point x="0" y="0.977273" />
                                <point x="0" y="0.0227273" />
                                <point x="1" y="0.0227273" />
                                <point x="1" y="0.977273" />
                            </collision-poly>
                        </frame>
                    </animation>
                    <animation framecount="5" loop="1" name="Fire" pingpong="0" repeatcount="1" repeatto="3" sid="4589316365590618" speed="30">
                        <frame duration="1" hotspotX="0.508772" hotspotY="0.5">
                            <collision-poly>
                                <point x="0" y="1" />
                                <point x="0" y="0.0909091" />
                                <point x="1" y="0.0909091" />
                                <point x="1" y="1" />
                            </collision-poly>
                        </frame>
                        <frame duration="1" hotspotX="0.508772" hotspotY="0.5">
                            <collision-poly>
                                <point x="0" y="1" />
                                <point x="0" y="0.0909091" />
                                <point x="1" y="0.0909091" />
                                <point x="1" y="1" />
                            </collision-poly>
                        </frame>
                        <frame duration="1" hotspotX="0.508772" hotspotY="0.5">
                            <collision-poly>
                                <point x="0" y="1" />
                                <point x="0" y="0.0227273" />
                                <point x="1" y="0.0227273" />
                                <point x="1" y="1" />
                            </collision-poly>
                        </frame>
                        <frame duration="1" hotspotX="0.508772" hotspotY="0.5">
                            <collision-poly>
                                <point x="0" y="1" />
                                <point x="0" y="0" />
                                <point x="1" y="0" />
                                <point x="1" y="1" />
                            </collision-poly>
                        </frame>
                        <frame duration="1" hotspotX="0.508772" hotspotY="0.5">
                            <collision-poly>
                                <point x="0" y="1" />
                                <point x="0" y="0" />
                                <point x="1" y="0" />
                                <point x="1" y="1" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="Platform1" sid="1226268899238104">
                <plugin id="NinePatch" />
                <instance-variables>
                    <instance-variable name="Direction" sid="4182532409429375" type="number" />
                    <instance-variable name="Speed" sid="9338468636982498" type="number" />
                    <instance-variable name="Reverse" sid="1757310495919901" type="boolean" />
                </instance-variables>
                <behaviors>
                    <behavior-type name="Jumpthru" sid="2517055594929798">
                        <behavior id="jumpthru" />
                    </behavior-type>
                    <behavior-type name="CustomMovement" sid="8396425350937595">
                        <behavior id="custom" />
                    </behavior-type>
                </behaviors>
                <container>
                    <type>Platform1</type>
                    <type>Platform2</type>
                </container>
                <texture />
            </object-type>
            <object-type name="Platform2" sid="6981383464931416">
                <plugin id="NinePatch" />
                <container>
                    <type>Platform1</type>
                    <type>Platform2</type>
                </container>
                <texture />
            </object-type>
            <object-type name="BoneStabV" sid="8140934880742138">
                <plugin id="NinePatch" />
                <texture />
            </object-type>
            <object-type name="BoneStabH" sid="6503092777075739">
                <plugin id="NinePatch" />
                <texture />
            </object-type>
            <object-type name="BoneStabWarn" sid="4163262150020477">
                <plugin id="NinePatch" />
                <instance-variables>
                    <instance-variable name="Direction" sid="1708321725631724" type="number" />
                    <instance-variable name="Distance" sid="1065051569636671" type="number" />
                    <instance-variable name="WarnTime" sid="4829472285865959" type="number" />
                    <instance-variable name="StayTime" sid="8313946059993536" type="number" />
                </instance-variables>
                <texture />
            </object-type>
            <object-type name="MenuBoneBottom" sid="761861833921609">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="State" sid="992680048340304" type="number" />
                    <instance-variable name="Button" sid="5567578753522818" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="4025981469830428" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" original-source="D:\Documents\Undertale Rip\Sprites\spr_s_boneloop_out_0.png">
                            <collision-poly>
                                <point x="0.142857" y="0.0454545" />
                                <point x="0.857143" y="0.0454545" />
                                <point x="0.857143" y="0.954545" />
                                <point x="0.142857" y="0.954545" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="MenuBoneLeft" sid="5246535965326995">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="Timer" sid="7519107776133302" type="number" />
                    <instance-variable name="Destroy" sid="6433670307252687" type="boolean" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="1189648859175843" speed="5">
                        <frame duration="1" hotspotX="0" hotspotY="0" original-source="D:\Documents\Undertale Rip\Sprites\spr_s_boneloop_out_0.png">
                            <collision-poly>
                                <point x="0.142857" y="0.0454545" />
                                <point x="0.857143" y="0.0454545" />
                                <point x="0.857143" y="0.954545" />
                                <point x="0.142857" y="0.954545" />
                            </collision-poly>
                        </frame>
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="GasterBlast2" sid="336730486351203">
                <plugin id="TiledBg" />
                <container>
                    <type>GasterBlaster</type>
                    <type>GasterBlastHit</type>
                    <type>GasterBlast1</type>
                    <type>GasterBlast2</type>
                    <type>GasterBlast3</type>
                </container>
                <texture />
            </object-type>
            <object-type name="GasterBlast3" sid="508841962091807">
                <plugin id="TiledBg" />
                <container>
                    <type>GasterBlaster</type>
                    <type>GasterBlastHit</type>
                    <type>GasterBlast1</type>
                    <type>GasterBlast2</type>
                    <type>GasterBlast3</type>
                </container>
                <texture />
            </object-type>
            <object-type name="GasterBlastHit" sid="165116925986465">
                <plugin id="TiledBg" />
                <container>
                    <type>GasterBlaster</type>
                    <type>GasterBlastHit</type>
                    <type>GasterBlast1</type>
                    <type>GasterBlast2</type>
                    <type>GasterBlast3</type>
                </container>
                <texture />
            </object-type>
        </object-folder>
        <object-folder name="Timeline">
            <object-type global="1" name="TLActionList" sid="456555951765879">
                <plugin id="Arr" />
            </object-type>
            <object-type global="1" name="TLCurrentLine" sid="3081225054711249">
                <plugin id="Arr" />
            </object-type>
            <object-type global="1" name="TLVars" sid="7317040439391986">
                <plugin id="Dictionary" />
            </object-type>
            <object-type global="1" name="TLLabels" sid="281757033099861">
                <plugin id="Dictionary" />
            </object-type>
        </object-folder>
        <object-folder name="Fonts">
            <object-type name="BattleFont" sid="6163397057824361">
                <plugin id="Spritefont2" />
                <texture original-source="C:\Users\Jcw87\Pictures\UndertaleBattleFont.png" />
            </object-type>
            <object-type name="SansFont" sid="5575857119740264">
                <plugin id="Spritefont2" />
                <texture original-source="C:\Users\Jcw87\Pictures\UndertaleSansFont.png" />
            </object-type>
            <object-type name="DefaultFont" sid="1422059525027614">
                <plugin id="Spritefont2" />
                <texture original-source="C:\Users\Jcw87\Pictures\UndertaleDefaultFont.png" />
            </object-type>
            <object-type name="DamageFont" sid="501546311307215">
                <plugin id="Spritefont2" />
                <texture original-source="C:\Users\Jcw87\Pictures\UndertaleDamageFont.png" />
            </object-type>
        </object-folder>
        <object-folder name="TouchUI">
            <object-type name="TouchA" sid="117524411669736">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="688431823067020" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0.5" />
                    </animation>
                    <animation framecount="1" loop="0" name="Pressed" pingpong="0" repeatcount="1" repeatto="0" sid="174733332464142" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0.5" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="TouchB" sid="428292736598660">
                <plugin id="Sprite" />
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="873294262795378" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0.5" />
                    </animation>
                    <animation framecount="1" loop="0" name="Pressed" pingpong="0" repeatcount="1" repeatto="0" sid="642935057171834" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0.5" />
                    </animation>
                </animation-folder>
            </object-type>
            <object-type name="TouchDPad" sid="293725615020106">
                <plugin id="Sprite" />
                <instance-variables>
                    <instance-variable name="TouchID" sid="310120484498810" type="number" />
                </instance-variables>
                <animation-folder>
                    <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="539337012850933" speed="5">
                        <frame duration="1" hotspotX="0.5" hotspotY="0.5" />
                    </animation>
                </animation-folder>
            </object-type>
        </object-folder>
        <object-type name="PlayerHeart" sid="5960708907117077">
            <plugin id="Sprite" />
            <instance-variables>
                <instance-variable name="Mode" sid="6313592074891908" type="number" />
                <instance-variable name="Slammed" sid="4448468745440906" type="boolean" />
                <instance-variable name="SlamDamage" sid="122041775148508" type="boolean" />
            </instance-variables>
            <behaviors>
                <behavior-type name="CustomMovement" sid="8958058217944609">
                    <behavior id="custom" />
                </behavior-type>
            </behaviors>
            <effects>
                <effect-type name="Tint">
                    <effect id="tint" />
                </effect-type>
            </effects>
            <animation-folder>
                <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="3948179004351251" speed="5">
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5">
                        <collision-poly>
                            <point x="0" y="1" />
                            <point x="0" y="0" />
                            <point x="1" y="0" />
                            <point x="1" y="1" />
                        </collision-poly>
                    </frame>
                </animation>
                <animation framecount="1" loop="0" name="Split" pingpong="0" repeatcount="1" repeatto="0" sid="9412816471889478" speed="5">
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5">
                        <collision-poly>
                            <point x="1" y="1" />
                            <point x="0" y="1" />
                            <point x="0" y="0" />
                            <point x="1" y="0" />
                        </collision-poly>
                    </frame>
                </animation>
            </animation-folder>
        </object-type>
        <object-type global="1" name="AttackList" sid="7966075756587832">
            <plugin id="Dictionary" />
        </object-type>
        <object-type name="MenuItem" sid="1630849692866887">
            <plugin id="Sprite" />
            <instance-variables>
                <instance-variable name="ID" sid="3974683574216717" type="number" />
                <instance-variable name="Text" sid="9053166434256353" type="string" />
                <instance-variable name="Action" sid="8424291498582479" type="string" />
                <instance-variable name="BackAction" sid="3202944525291714" type="string" />
                <instance-variable name="Created" sid="1711039613963512" type="boolean" />
            </instance-variables>
            <animation-folder>
                <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="155770205370032" speed="5">
                    <frame duration="1" hotspotX="0" hotspotY="0" />
                </animation>
            </animation-folder>
        </object-type>
        <object-type global="1" name="PlayerItems" sid="2840436798779952">
            <plugin id="Arr" />
        </object-type>
        <object-type global="1" name="ItemDB" sid="799284438884525">
            <plugin id="Arr" />
        </object-type>
        <object-type name="HeartShard" sid="4095409948730649">
            <plugin id="Sprite" />
            <behaviors>
                <behavior-type name="CustomMovement" sid="7822586923915929">
                    <behavior id="custom" />
                </behavior-type>
            </behaviors>
            <animation-folder>
                <animation framecount="4" loop="1" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="1279672314658953" speed="15">
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_heartshards_0.png">
                        <collision-poly>
                            <point x="0.3125" y="0.3125" />
                            <point x="0.5" y="0.375" />
                            <point x="0.625" y="0.4375" />
                            <point x="0.6875" y="0.5" />
                            <point x="0.75" y="0.6875" />
                            <point x="0.5" y="0.625" />
                            <point x="0.375" y="0.5" />
                        </collision-poly>
                    </frame>
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_heartshards_1.png">
                        <collision-poly>
                            <point x="0.375" y="0.4375" />
                            <point x="0.5" y="0.375" />
                            <point x="0.625" y="0.4375" />
                            <point x="0.6875" y="0.5" />
                            <point x="0.625" y="0.625" />
                            <point x="0.5" y="0.6875" />
                            <point x="0.375" y="0.625" />
                            <point x="0.3125" y="0.5" />
                        </collision-poly>
                    </frame>
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_heartshards_2.png">
                        <collision-poly>
                            <point x="0.3125" y="0.25" />
                            <point x="0.75" y="0.25" />
                            <point x="0.75" y="0.75" />
                            <point x="0.3125" y="0.75" />
                        </collision-poly>
                    </frame>
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5" original-source="C:\Users\Jcw87\Documents\Undertale Rip\Sprites\spr_heartshards_3.png">
                        <collision-poly>
                            <point x="0.3125" y="0.375" />
                            <point x="0.6875" y="0.375" />
                            <point x="0.6875" y="0.6875" />
                            <point x="0.3125" y="0.6875" />
                        </collision-poly>
                    </frame>
                </animation>
            </animation-folder>
        </object-type>
        <object-type global="1" name="AttackLoader" sid="6354874427432412">
            <plugin id="Arr" />
        </object-type>
        <object-type global="1" name="MenuStack" sid="1417790766954608">
            <plugin id="Arr" />
        </object-type>
        <object-type name="FileChooser" sid="8898820624476746">
            <plugin id="filechooser" />
        </object-type>
        <object-type name="Browser" sid="4029960250195912">
            <plugin id="Browser" />
        </object-type>
        <object-type name="PlayerHitbox" sid="728293317807613">
            <plugin id="Sprite" />
            <animation-folder>
                <animation framecount="1" loop="0" name="Default" pingpong="0" repeatcount="1" repeatto="0" sid="405047860068601" speed="5">
                    <frame duration="1" hotspotX="0.5" hotspotY="0.5" />
                </animation>
            </animation-folder>
        </object-type>
    </object-folder>
    <families>
        <family name="BoneStab" plugin-id="NinePatch" sid="9321183475132962">
            <members>
                <member>BoneStabH</member>
                <member>BoneStabV</member>
            </members>
            <instance-variables>
                <instance-variable name="Direction" sid="9712410343672045" type="number" />
                <instance-variable name="Distance" sid="1340413306933887" type="number" />
                <instance-variable name="DestX" sid="7626491151499593" type="number" />
                <instance-variable name="DestY" sid="4662037835176925" type="number" />
                <instance-variable name="StayTime" sid="4383237448031349" type="number" />
                <instance-variable name="Reverse" sid="510004270528703" type="boolean" />
            </instance-variables>
        </family>
        <family name="Bone" plugin-id="NinePatch" sid="2013892859044994">
            <members>
                <member>BoneH</member>
                <member>BoneV</member>
            </members>
            <instance-variables>
                <instance-variable name="Direction" sid="2353520185577067" type="number" />
                <instance-variable name="Speed" sid="8541710245044527" type="number" />
            </instance-variables>
        </family>
        <family name="RPGText" plugin-id="Spritefont2" sid="8627438680975019">
            <members>
                <member>BattleFont</member>
                <member>DamageFont</member>
                <member>DefaultFont</member>
                <member>SansFont</member>
            </members>
            <instance-variables>
                <instance-variable name="Name" sid="8126938230629388" type="string" />
                <instance-variable name="Voice" sid="7739643538975967" type="string" />
                <instance-variable name="FullText" sid="4090187800761089" type="string" />
                <instance-variable name="EndFunc" sid="8768540262486332" type="string" />
                <instance-variable name="Interactive" sid="2703717793020135" type="boolean" />
                <instance-variable name="CurrentChar" sid="8429195992300595" type="number" />
                <instance-variable name="T" sid="9067313364631326" type="number" />
                <instance-variable name="Timeout" sid="4487571781562274" type="number" />
            </instance-variables>
            <effects>
                <effect-type name="Tint">
                    <effect id="tint" />
                </effect-type>
            </effects>
        </family>
        <family name="UIButtons" plugin-id="Sprite" sid="9802428034038081">
            <members>
                <member>UIAct</member>
                <member>UIFight</member>
                <member>UIItem</member>
                <member>UIMercy</member>
            </members>
            <instance-variables>
                <instance-variable name="ID" sid="3161584809306413" type="number" />
                <instance-variable name="Action" sid="5414051533652294" type="string" />
            </instance-variables>
        </family>
        <family name="Attack9Patch" plugin-id="NinePatch" sid="9590353435551898">
            <members>
                <member>BoneH</member>
                <member>BoneStabH</member>
                <member>BoneStabV</member>
                <member>BoneStabWarn</member>
                <member>BoneV</member>
                <member>Platform1</member>
                <member>Platform2</member>
            </members>
            <instance-variables>
                <instance-variable name="Damage" sid="6677681737098705" type="number" />
                <instance-variable name="Karma" sid="6030229564139285" type="number" />
                <instance-variable name="Color" sid="821640292253391" type="number" />
            </instance-variables>
            <effects>
                <effect-type name="Tint">
                    <effect id="tint" />
                </effect-type>
            </effects>
        </family>
        <family name="AttackSprite" plugin-id="Sprite" sid="6631597198329078">
            <members>
                <member>GasterBlaster</member>
                <member>MenuBoneBottom</member>
                <member>MenuBoneLeft</member>
            </members>
            <instance-variables>
                <instance-variable name="Damage" sid="1009715326578042" type="number" />
                <instance-variable name="Karma" sid="1305040970412396" type="number" />
            </instance-variables>
        </family>
        <family name="AttackTiled" plugin-id="TiledBg" sid="9784977049754561">
            <members>
                <member>GasterBlastHit</member>
            </members>
            <instance-variables>
                <instance-variable name="Damage" sid="5846064141855004" type="number" />
                <instance-variable name="Karma" sid="4419610502870706" type="number" />
            </instance-variables>
        </family>
        <family name="TouchButton" plugin-id="Sprite" sid="902272746554209">
            <members>
                <member>TouchA</member>
                <member>TouchB</member>
            </members>
            <instance-variables>
                <instance-variable name="TouchID" sid="636958093485166" type="number" />
                <instance-variable name="Pressed" sid="875789127674825" type="boolean" />
            </instance-variables>
        </family>
    </families>
    <layout-folder>
        <layout>BattleScreen.xml</layout>
        <layout>System.xml</layout>
        <layout>MainMenu.xml</layout>
    </layout-folder>
    <event-folder>
        <event-sheet>Battle.xml</event-sheet>
        <event-sheet>InputManagement.xml</event-sheet>
        <event-sheet>Globals.xml</event-sheet>
        <event-sheet>Timeline.xml</event-sheet>
        <event-sheet>Fonts.xml</event-sheet>
        <event-sheet>RPGText.xml</event-sheet>
        <event-sheet>Items.xml</event-sheet>
        <event-sheet>AttackLoader.xml</event-sheet>
        <event-sheet>MainMenu.xml</event-sheet>
        <event-sheet>Menus.xml</event-sheet>
    </event-folder>
    <global-instances>
        <global-instance type="Gamepad" uid="8">
            <properties>
                <analog-deadzone>25</analog-deadzone>
            </properties>
        </global-instance>
        <global-instance type="Keyboard" uid="10" />
        <global-instance type="Function" uid="17" />
        <global-instance type="AJAX" uid="30" />
        <global-instance type="Audio" uid="33">
            <properties>
                <timescale-audio>Off</timescale-audio>
                <saveload>All</saveload>
                <play-in-background>No</play-in-background>
                <positioned-audio></positioned-audio>
                <panning-model>HRTF</panning-model>
                <distance-model>Inverse</distance-model>
                <listener-z-height>600</listener-z-height>
                <reference-distance>600</reference-distance>
                <maximum-distance>10000</maximum-distance>
                <roll-off-factor>1</roll-off-factor>
            </properties>
        </global-instance>
        <global-instance type="Browser" uid="54" />
        <global-instance type="Touch" uid="58">
            <properties>
                <use-mouse-input>Yes</use-mouse-input>
            </properties>
        </global-instance>
    </global-instances>
    <sounds-folder>
        <file name="Ding.ogg" />
        <file name="PlayerFight.ogg" />
        <file name="PlayerDamaged.ogg" />
        <file name="SansSpeak.ogg" />
        <file name="GasterBlaster.ogg" />
        <file name="BoneStab.ogg" />
        <file name="Warning.ogg" />
        <file name="HeartShatter.ogg" />
        <file name="GasterBlast.ogg" />
        <file name="Flash.ogg" />
        <file name="Slam.ogg" />
        <file name="MenuSelect.ogg" />
        <file name="HeartSplit.ogg" />
        <file name="MenuCursor.ogg" />
        <file name="BattleText.ogg" />
        <file name="PlayerHeal.ogg" />
        <file name="GasterBlast2.ogg" />
    </sounds-folder>
    <music-folder>
        <file name="mus_zz_megalovania.ogg" />
    </music-folder>
    <files-folder>
        <file-folder name="Icons">
            <file name="icon-16.png" />
            <file name="icon-32.png" />
            <file name="icon-114.png" />
            <file name="icon-128.png" />
            <file name="icon-256.png" />
            <file name="loading-logo.png" />
        </file-folder>
        <file name="sans_intro.csv" />
        <file name="sans_bonegap1.csv" />
        <file name="sans_bonegap2.csv" />
        <file name="sans_bluebone.csv" />
        <file name="sans_platforms1.csv" />
        <file name="sans_platforms2.csv" />
        <file name="sans_platforms3.csv" />
        <file name="sans_platforms4.csv" />
        <file name="sans_platformblaster.csv" />
        <file name="sans_platforms4hard.csv" />
        <file name="sans_boneslideh.csv" />
        <file name="sans_bonegap1fast.csv" />
        <file name="sans_platformblasterfast.csv" />
        <file name="sans_spare.csv" />
        <file name="sans_bonestab1.csv" />
        <file name="sans_bonestab2.csv" />
        <file name="sans_boneslidev.csv" />
        <file name="sans_multi1.csv" />
        <file name="sans_randomblaster1.csv" />
        <file name="sans_multi2.csv" />
        <file name="sans_randomblaster2.csv" />
        <file name="sans_bonestab3.csv" />
        <file name="sans_multi3.csv" />
        <file name="sans_final.csv" />
    </files-folder>
</c2project>
