# CandiceLao21155085
COMP826_milestone2
// Overlay use className props to pass style properties to child component.
// To make this component work add className props to your child component manually.
// Here an example: https://gist.github.com/Miniplop/8f87608f8100e758fa5a4eb46f9d151f

import React from "react";
import {
  FbImg1590659851920Edit42299739636566,
  MapSearch
} from "components";
import styles from "./Num826Total.module.scss";

const Num826Total = () => {
  return (
    <div className={styles.num826Total}>
      <div className={styles.flexWrapperSeventyTwo}>
        <div className={styles.iPhone13ProMaxHomePage}>
          <div className={styles.flexWrapperSeventySix}>
            <img
              alt=""
              className={styles.bluetooth}
              src="https://static.overlay-tech.com/assets/6a76da22-189f-49e1-afcb-e1eee15fe7d7.svg"
            />
            <p className={styles.num915}>9:15</p>
            <img
              alt=""
              className={styles.sim1Signal}
              src="https://static.overlay-tech.com/assets/7a5d3f62-c3ee-4218-844c-1ce60e9867a7.svg"
            />
            <img
              alt=""
              className={styles.wiFiSignal}
              src="https://static.overlay-tech.com/assets/35cbd4d5-65e7-4e6d-846e-82d5741151aa.svg"
            />
            <img
              alt=""
              className={styles.battery}
              src="https://static.overlay-tech.com/assets/6bdb4a41-fbcc-41f3-aa1e-53b7bda81b76.svg"
            />
          </div>
          <div className={styles.relativeWrapperSeventeen}>
            <div className={styles.rectangle2} />
            <div className={styles.rectangle1} />
            <div className={styles.rectangle1Two} />
            <div className={styles.rectangle1Three} />
            <div className={styles.rectangle2Two} />
            <div className={styles.flexWrapperThirtySix}>
              <img
                alt=""
                className={styles.smallCar}
                src="https://static.overlay-tech.com/assets/b90870df-4134-4ead-85b4-f29c5a1a4c49.svg"
              />
              <div className={styles.ellipse2} />
            </div>
            <div className={styles.rectangle47} />
            <p className={styles.olderPeopleMode}>
              OLDER PEOPLE MODE
            </p>
          </div>
          <div className={styles.relativeWrapperEighteen}>
            <div className={styles.flexWrapperThirty}>
              <div className={styles.rectangle3} />
            </div>
            <p className={styles.signIn}>Sign In</p>
            <p className={styles.arDrivingMobile}>
              AR-Driving <br />
              Mobile
            </p>
            <img
              alt=""
              className={styles.group2}
              src="https://static.overlay-tech.com/assets/8b3e8eac-f993-4cdc-8344-ec084dafdf1f.svg"
            />
          </div>
          <div className={styles.flexWrapperThirtyOne}>
            <div className={styles.rectangle6} />
            <p className={styles.register}>Register</p>
          </div>
          <p className={styles.forgetPassword}>
            Forget Password
          </p>
          <div className={styles.relativeWrapperTwenty}>
            <div className={styles.flexWrapperThirtyFive}>
              <div className={styles.rectangle27} />
            </div>
            <p className={styles.browseOnTheMap}>
              Browse on the Map
            </p>
          </div>
          <div className={styles.flexWrapperThirtyFour}>
            <div className={styles.rectangle25} />
            <p className={styles.quickGuide}>Quick Guide</p>
          </div>
          <div className={styles.relativeWrapperTwenty}>
            <div className={styles.flexWrapperThirtyThree}>
              <div className={styles.rectangle23} />
            </div>
            <p className={styles.contactUs}>Contact Us</p>
          </div>
          <div className={styles.flexWrapperThirtyTwo}>
            <div className={styles.rectangle21} />
            <p className={styles.feedback}>Feedback</p>
          </div>
        </div>
        <div className={styles.iPhone13ProMaxHomePageTwo}>
          <div className={styles.flexWrapperSeventySeven}>
            <img
              alt=""
              className={styles.bluetoothTwo}
              src="https://static.overlay-tech.com/assets/3cbf989d-788b-421c-a678-717526405206.svg"
            />
            <p className={styles.num915Two}>9:15</p>
            <img
              alt=""
              className={styles.sim1SignalTwo}
              src="https://static.overlay-tech.com/assets/2b8ad35c-e393-40db-84b3-9775f217af36.svg"
            />
            <img
              alt=""
              className={styles.wiFiSignalTwo}
              src="https://static.overlay-tech.com/assets/660fb4d2-4ba5-4585-b776-0c8b20b1565e.svg"
            />
            <img
              alt=""
              className={styles.batteryTwo}
              src="https://static.overlay-tech.com/assets/f5437ab8-eeee-441f-b8bd-07cda92f0d79.svg"
            />
          </div>
          <div
            className={styles.relativeWrapperThirtyEight}
          >
            <div className={styles.rectangle2Three} />
            <div className={styles.rectangle1Four} />
            <div className={styles.rectangle1Five} />
            <div className={styles.rectangle1Six} />
            <div className={styles.rectangle2Four} />
            <div className={styles.flexWrapperSixtyNine}>
              <img
                alt=""
                className={styles.smallCar}
                src="https://static.overlay-tech.com/assets/55813663-f5e5-4de1-a8e6-e7e7f88728e7.svg"
              />
              <div className={styles.ellipse2Two} />
            </div>
            <p className={styles.arDrivingMobile}>
              AR-Driving <br />
              Mobile
            </p>
            <img
              alt=""
              className={styles.group2}
              src="https://static.overlay-tech.com/assets/2bf74553-5c4d-4ff3-8655-ae980df6272a.svg"
            />
            <div className={styles.rectangle47Two} />
            <p className={styles.normalMode}>
              NORMAL <br />
              MODE
            </p>
          </div>
          <div className={styles.flexWrapperSeventyEight}>
            <div className={styles.flexWrapperSixtyFour}>
              <div className={styles.rectangle3Two} />
              <p className={styles.signInTwo}>Sign In</p>
            </div>
            <div className={styles.flexWrapperSixtyThree}>
              <div className={styles.rectangle6Two} />
              <p className={styles.registerTwo}>Register</p>
            </div>
          </div>
          <p className={styles.forgetPasswordTwo}>
            Forget Password
          </p>
          <div className={styles.relativeWrapperForty}>
            <div className={styles.flexWrapperSixtyEight}>
              <div className={styles.rectangle27Two} />
            </div>
            <p className={styles.browseOnTheMapTwo}>
              Browse on the Map
            </p>
          </div>
          <div className={styles.flexWrapperSixtySeven}>
            <div className={styles.rectangle25Two} />
            <p className={styles.quickGuideTwo}>
              Quick Guide
            </p>
          </div>
          <div className={styles.relativeWrapperThirtyNine}>
            <div className={styles.flexWrapperSixtySix}>
              <div className={styles.rectangle23Two} />
            </div>
            <p className={styles.contactUsTwo}>
              Contact Us
            </p>
          </div>
          <div className={styles.flexWrapperSixtyFive}>
            <div className={styles.rectangle21Two} />
            <p className={styles.feedbackTwo}>Feedback</p>
          </div>
        </div>
      </div>
      <div className={styles.flexWrapperSeventyThree}>
        <div className={styles.feedbackPage}>
          <div className={styles.flexWrapperSeventyNine}>
            <img
              alt=""
              className={styles.bluetooth}
              src="https://static.overlay-tech.com/assets/f3283e10-23e3-432b-8283-39aaae70a748.svg"
            />
            <p className={styles.num915}>9:15</p>
            <img
              alt=""
              className={styles.sim1Signal}
              src="https://static.overlay-tech.com/assets/0905bf7c-bf29-4a8b-98ff-723f5d2dec3a.svg"
            />
            <img
              alt=""
              className={styles.wiFiSignal}
              src="https://static.overlay-tech.com/assets/37b3cf49-93c7-4801-adcb-382d1595b05f.svg"
            />
            <img
              alt=""
              className={styles.battery}
              src="https://static.overlay-tech.com/assets/8ec6e60b-8c8f-4a7c-be06-dabedcd7e7f0.svg"
            />
          </div>
          <div className={styles.flexWrapperEighty}>
            <img
              alt=""
              className={styles.toHomePage}
              src="https://static.overlay-tech.com/assets/2dbdc64d-df19-48ae-9529-f4324e323e40.svg"
            />
            <img
              alt=""
              className={styles.back}
              src="https://static.overlay-tech.com/assets/6e4431f6-d3d4-406c-bf26-793ebac1b7a7.svg"
            />
          </div>
          <div className={styles.undrawByMyCarReJ3jt1}>
            <img
              alt=""
              className={styles.vector}
              src="https://static.overlay-tech.com/assets/dd0faa1a-e263-4625-8242-45ca6cb7337a.svg"
            />
            <div className={styles.groupSeven}>
              <div className={styles.relativeWrapperSix}>
                <img
                  alt=""
                  className={styles.group}
                  src="https://static.overlay-tech.com/assets/7a53e53f-9f29-47f0-88da-b9e2d24ec062.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwo}
                  src="https://static.overlay-tech.com/assets/7161bf26-1ce5-430e-8148-9f4c3693c7be.svg"
                />
                <img
                  alt=""
                  className={styles.vectorThree}
                  src="https://static.overlay-tech.com/assets/9aaf2620-88f6-4482-aa00-9e55d93736a7.svg"
                />
                <img
                  alt=""
                  className={styles.groupTwo}
                  src="https://static.overlay-tech.com/assets/62a99ad7-2fbc-4a89-a35f-31d52b092879.svg"
                />
                <img
                  alt=""
                  className={styles.vectorFour}
                  src="https://static.overlay-tech.com/assets/c63f0e52-b616-410d-9c49-d8190899a2dd.svg"
                />
                <img
                  alt=""
                  className={styles.groupThree}
                  src="https://static.overlay-tech.com/assets/01cc90b4-0f3c-4921-8f8e-7d4fd539c1b3.svg"
                />
                <img
                  alt=""
                  className={styles.vectorFive}
                  src="https://static.overlay-tech.com/assets/51ad7eb9-eaaa-4ad6-a113-31990a245346.svg"
                />
              </div>
              <div className={styles.relativeWrapperSeven}>
                <img
                  alt=""
                  className={styles.groupFour}
                  src="https://static.overlay-tech.com/assets/3855e092-a77c-4121-972f-875238bbb415.svg"
                />
                <img
                  alt=""
                  className={styles.vectorSix}
                  src="https://static.overlay-tech.com/assets/c0ada40b-fa3d-4c20-8f5a-7a5a6b730857.svg"
                />
                <div className={styles.groupSix}>
                  <img
                    alt=""
                    className={styles.groupFive}
                    src="https://static.overlay-tech.com/assets/a8b686fa-c44a-4ce0-ac6b-22f35e5af1f9.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorSeven}
                    src="https://static.overlay-tech.com/assets/983a6edb-cba8-495d-9418-ab0fefc79820.svg"
                  />
                </div>
              </div>
            </div>
            <div className={styles.flexWrapperFifteen}>
              <img
                alt=""
                className={styles.vectorEight}
                src="https://static.overlay-tech.com/assets/d79ba224-21ba-4d02-89ba-61c9694dac01.svg"
              />
            </div>
            <div className={styles.groupEleven}>
              <img
                alt=""
                className={styles.groupEight}
                src="https://static.overlay-tech.com/assets/6b464476-18e0-4cb6-81c0-54e2e0d8e1f1.svg"
              />
              <img
                alt=""
                className={styles.vectorNine}
                src="https://static.overlay-tech.com/assets/eace67e7-2d3f-4182-bfed-31dc3e2d2a1b.svg"
              />
              <img
                alt=""
                className={styles.vectorTen}
                src="https://static.overlay-tech.com/assets/603dcc94-a492-4be6-86c8-69eefda448ba.svg"
              />
              <img
                alt=""
                className={styles.vectorSeven}
                src="https://static.overlay-tech.com/assets/04e3c722-f8e7-489f-82e7-f1fc23488607.svg"
              />
              <img
                alt=""
                className={styles.vectorEleven}
                src="https://static.overlay-tech.com/assets/bc574b0d-475e-409c-8f4c-da4e6532b209.svg"
              />
              <img
                alt=""
                className={styles.groupNine}
                src="https://static.overlay-tech.com/assets/951a755d-7893-4e6a-8a6b-b85d4c1f44d1.svg"
              />
              <img
                alt=""
                className={styles.groupTen}
                src="https://static.overlay-tech.com/assets/9346cddd-ea82-4494-b2f0-f2d72145139b.svg"
              />
              <img
                alt=""
                className={styles.vectorTwelve}
                src="https://static.overlay-tech.com/assets/5afef6b3-45bb-4d15-b56d-ad5b49e7a3a1.svg"
              />
              <img
                alt=""
                className={styles.vectorThirteen}
                src="https://static.overlay-tech.com/assets/1ee6955c-dc90-4981-b6f8-1c02158c6f74.svg"
              />
            </div>
          </div>
          <div className={styles.relativeWrapperEleven}>
            <p
              className={
                styles.howDoYouThinkAboutThisAppsPageD
              }
            >
              How do you think about this APP’s page design?
            </p>
            <div className={styles.flexWrapperTwenty}>
              <div className={styles.rectangle41} />
              <div className={styles.rectangle44} />
              <div className={styles.rectangle43} />
              <p className={styles.bad}>Bad</p>
              <div className={styles.rectangle42} />
              <p className={styles.excellent}>Excellent</p>
              <p className={styles.good}>Good</p>
            </div>
          </div>
          <div className={styles.relativeWrapperTwelve}>
            <p className={styles.howIsThisAppsUsibility}>
              How is this APP’s usibility?
            </p>
            <div className={styles.flexWrapperTwenty}>
              <div className={styles.rectangle41} />
              <div className={styles.rectangle44} />
              <div className={styles.rectangle43} />
              <p className={styles.badTwo}>Bad</p>
              <div className={styles.rectangle42} />
              <p className={styles.excellentTwo}>
                Excellent
              </p>
              <p className={styles.goodTwo}>Good</p>
            </div>
          </div>
          <div className={styles.relativeWrapperThirteen}>
            <p
              className={
                styles.howWouldYouRecommendThisAppToYour
              }
            >
              How would you recommend this APP to your
              friends? Rate from 1 to 3.
            </p>
            <div className={styles.flexWrapperTwentyTwo}>
              <div className={styles.rectangle41} />
              <div className={styles.rectangle44} />
              <div className={styles.rectangle43} />
              <p className={styles.num1}>1</p>
              <div className={styles.rectangle42} />
              <p className={styles.num3}>3</p>
              <p className={styles.num2}>2</p>
            </div>
          </div>
          <div className={styles.flexWrapperNineteen}>
            <div className={styles.rectangle6Three} />
            <p className={styles.yourPhoneNumberOrEmail}>
              Your Phone Number or Email
            </p>
          </div>
          <div className={styles.relativeWrapperTen}>
            <div className={styles.flexWrapperEighteen}>
              <div className={styles.rectangle3Three} />
            </div>
            <p
              className={
                styles.pleaseGiveSomeRecommendationHere
              }
            >
              Please give some recommendation here...
            </p>
            <div className={styles.undrawTeamUpRe84ok1}>
              <img
                alt=""
                className={styles.vectorFourteen}
                src="https://static.overlay-tech.com/assets/1da1c344-1d63-43b8-b4c9-10ffd61a22a5.svg"
              />
              <img
                alt=""
                className={styles.groupTwelve}
                src="https://static.overlay-tech.com/assets/5090c335-e1fe-454f-af6e-ab4732163d68.svg"
              />
              <div className={styles.flexWrapperSeventeen}>
                <img
                  alt=""
                  className={styles.vectorFifteen}
                  src="https://static.overlay-tech.com/assets/cf404de5-fc37-4bb2-8297-fc726e08377e.svg"
                />
                <div className={styles.groupSixteen}>
                  <div
                    className={styles.relativeWrapperNine}
                  >
                    <img
                      alt=""
                      className={styles.vectorSixteen}
                      src="https://static.overlay-tech.com/assets/e37fa13b-a1fa-414c-8d0a-4abc21b7dbff.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorSeven}
                      src="https://static.overlay-tech.com/assets/9fa2c524-aee1-42fd-92b6-52a1f9a99abf.svg"
                    />
                  </div>
                  <div
                    className={styles.relativeWrapperEight}
                  >
                    <img
                      alt=""
                      className={
                        styles.uuidD0b765428f084363846d0cc3b89caf2
                      }
                      src="https://static.overlay-tech.com/assets/3a951ca1-8102-4dad-a54a-5572027cfd9f.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorSeventeen}
                      src="https://static.overlay-tech.com/assets/d0155643-b8c1-40ff-9410-cf43aa3429bb.svg"
                    />
                    <img
                      alt=""
                      className={styles.groupThirteen}
                      src="https://static.overlay-tech.com/assets/4d44b6ac-9ebb-4c90-af69-21a15c8bd49a.svg"
                    />
                    <img
                      alt=""
                      className={styles.groupFourteen}
                      src="https://static.overlay-tech.com/assets/f6f722c2-b1aa-4f92-948e-3f901bb167e8.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorEighteen}
                      src="https://static.overlay-tech.com/assets/46d142a2-5dcf-410c-b775-609bca78a62b.svg"
                    />
                    <img
                      alt=""
                      className={styles.groupFifteen}
                      src="https://static.overlay-tech.com/assets/a2aba601-c517-4f32-b5f0-06396575d887.svg"
                    />
                  </div>
                </div>
              </div>
              <div className={styles.groupEighteen}>
                <img
                  alt=""
                  className={
                    styles.uuidBa1531a6E7ab4297B9961d676f43fe3
                  }
                  src="https://static.overlay-tech.com/assets/405bceef-b94f-42c9-bc81-3690bac9eeed.svg"
                />
                <img
                  alt=""
                  className={styles.vectorNineteen}
                  src="https://static.overlay-tech.com/assets/d34f49ea-6d15-403c-81e4-dd485377f71a.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwenty}
                  src="https://static.overlay-tech.com/assets/71cba34d-b11e-4d30-9ddf-d4d06768c78e.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwentyOne}
                  src="https://static.overlay-tech.com/assets/54944ed7-3bf9-45a8-9ba5-49e709c6f310.svg"
                />
                <img
                  alt=""
                  className={styles.vectorSeven}
                  src="https://static.overlay-tech.com/assets/805c6e36-ab7f-4cba-bde2-76834a6bfadb.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwentyTwo}
                  src="https://static.overlay-tech.com/assets/eee02a6e-4568-474a-99fe-58f5e4073fd4.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwentyThree}
                  src="https://static.overlay-tech.com/assets/f7dbe190-9148-4603-ba27-f793251c1d85.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwentyFour}
                  src="https://static.overlay-tech.com/assets/41443c08-de35-4702-9607-330cb1c29449.svg"
                />
                <img
                  alt=""
                  className={styles.vectorTwentyFive}
                  src="https://static.overlay-tech.com/assets/1ad2637c-99b9-407e-8d36-2dbfe1b39614.svg"
                />
                <img
                  alt=""
                  className={styles.groupSeventeen}
                  src="https://static.overlay-tech.com/assets/4b9ba297-1d51-4d9a-b0d8-71575f40aee1.svg"
                />
                <div className={styles.flexWrapperSixteen}>
                  <img
                    alt=""
                    className={styles.vectorSeven}
                    src="https://static.overlay-tech.com/assets/08273bbf-6d63-4a56-8544-609d0c7cade3.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorTwentySix}
                    src="https://static.overlay-tech.com/assets/60133367-a76c-4f59-9d14-6e0e0d36e5f4.svg"
                  />
                </div>
              </div>
              <img
                alt=""
                className={styles.groupNineteen}
                src="https://static.overlay-tech.com/assets/1ac5b14e-9613-465a-8d42-6fcf909a6c64.svg"
              />
            </div>
            <div className={styles.flexWrapperTwentyThree}>
              <div className={styles.rectangle46} />
              <p className={styles.send}>Send</p>
            </div>
          </div>
        </div>
        <div className={styles.signInPage}>
          <div className={styles.relativeWrapperFive}>
            <div className={styles.flexWrapperEleven}>
              <div className={styles.rectangle9} />
            </div>
            <p className={styles.userName}>User Name</p>
            <div className={styles.home} />
            <div className={styles.home} />
          </div>
          <p className={styles.forgetPasswordThree}>
            Forget Password
          </p>
          <div className={styles.relativeWrapperThree}>
            <div className={styles.ellipse4} />
            <div className={styles.ellipse6} />
            <div className={styles.ellipse3} />
            <div className={styles.flexWrapperTwelve}>
              <div className={styles.rectangle3Three} />
            </div>
            <div className={styles.flexWrapperThirteen}>
              <div className={styles.flexWrapperFourteen}>
                <div className={styles.rectangle3} />
              </div>
              <p className={styles.signInThree}>Sign In</p>
            </div>
          </div>
          <div className={styles.relativeWrapperFour}>
            <div className={styles.ellipse5} />
            <div className={styles.flexWrapperTen}>
              <div className={styles.ellipse2Three} />
              <img
                alt=""
                className={styles.sim1SignalThree}
                src="https://static.overlay-tech.com/assets/4220ac0e-687c-45f3-aad5-358c5608c863.svg"
              />
              <img
                alt=""
                className={styles.wiFiSignalThree}
                src="https://static.overlay-tech.com/assets/669e4fc6-52e7-4fd0-8bc0-359a8145ad90.svg"
              />
              <img
                alt=""
                className={styles.batteryThree}
                src="https://static.overlay-tech.com/assets/6a8b6417-0f73-4a78-a2dd-76dc0c54761a.svg"
              />
              <div className={styles.ellipse3Two} />
              <div className={styles.ellipse8} />
              <div className={styles.ellipse9} />
              <p className={styles.num915Three}>9:15</p>
              <img
                alt=""
                className={styles.bluetoothThree}
                src="https://static.overlay-tech.com/assets/f5abcfab-10fe-45f3-bbef-ea97531d94de.svg"
              />
              <img
                alt=""
                className={styles.backTwo}
                src="https://static.overlay-tech.com/assets/c5a5ec22-d61d-4b78-89e2-bad709586b0f.svg"
              />
              <img
                alt=""
                className={styles.toHomePageTwo}
                src="https://static.overlay-tech.com/assets/6b890c3f-7725-4149-865f-9130bf1e83be.svg"
              />
            </div>
            <img
              alt=""
              className={styles.undrawTutorialVideoReWepc1}
              src="https://static.overlay-tech.com/assets/f99c0136-f412-4435-a369-74d96c775d63.svg"
            />
          </div>
          <p className={styles.password}>Password</p>
        </div>
        <div className={styles.feedbackPageTwo}>
          <div className={styles.flexWrapperEightyOne}>
            <div className={styles.flexWrapperEightyTwo}>
              <img
                alt=""
                className={styles.bluetoothFour}
                src="https://static.overlay-tech.com/assets/6b8a1d96-9213-4cd7-9214-e8cf57c3b8b6.svg"
              />
              <img
                alt=""
                className={styles.toHomePageThree}
                src="https://static.overlay-tech.com/assets/220faf11-1331-49aa-8d8f-7a48e45a8649.svg"
              />
            </div>
            <div className={styles.flexWrapperEightyThree}>
              <p className={styles.num915Four}>9:15</p>
              <img
                alt=""
                className={styles.backThree}
                src="https://static.overlay-tech.com/assets/30320527-f5ff-4e22-80b8-d4eb88faef1a.svg"
              />
            </div>
            <div
              className={styles.relativeWrapperTwentyNine}
            >
              <img
                alt=""
                className={styles.sim1SignalFour}
                src="https://static.overlay-tech.com/assets/1aac5dc0-0ccd-400f-b77c-33d80a2222d6.svg"
              />
              <div
                className={styles.undrawByMyCarReJ3jt1Two}
              >
                <img
                  alt=""
                  className={styles.vectorTwentySeven}
                  src="https://static.overlay-tech.com/assets/aab55610-e64a-4e37-9979-4d88f4a37276.svg"
                />
                <div className={styles.groupTwentySix}>
                  <div
                    className={
                      styles.relativeWrapperTwentySeven
                    }
                  >
                    <img
                      alt=""
                      className={styles.groupTwenty}
                      src="https://static.overlay-tech.com/assets/903cbfa1-a024-42da-9cb6-793ab17d6874.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorTwentyEight}
                      src="https://static.overlay-tech.com/assets/bdc117cb-522e-48c4-8d5d-56878b884748.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorTwentyNine}
                      src="https://static.overlay-tech.com/assets/f765b2fd-f733-484f-9df7-686b47e53c38.svg"
                    />
                    <img
                      alt=""
                      className={styles.groupTwentyOne}
                      src="https://static.overlay-tech.com/assets/1332a513-f7e0-4ae9-b861-f8cc4237bef1.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorThirty}
                      src="https://static.overlay-tech.com/assets/129c6389-bac7-4610-8984-e5b659d729d8.svg"
                    />
                    <img
                      alt=""
                      className={styles.groupTwentyTwo}
                      src="https://static.overlay-tech.com/assets/f27807bd-4c97-4250-b8b5-6f3f563f52ba.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorThirtyOne}
                      src="https://static.overlay-tech.com/assets/20e234fb-4697-483d-9fa8-4b1a1cc10bef.svg"
                    />
                  </div>
                  <div
                    className={styles.relativeWrapperSeven}
                  >
                    <img
                      alt=""
                      className={styles.groupTwentyThree}
                      src="https://static.overlay-tech.com/assets/2fa4e536-ea0d-46b8-ad31-87f248713765.svg"
                    />
                    <img
                      alt=""
                      className={styles.vectorThirtyTwo}
                      src="https://static.overlay-tech.com/assets/8c4486f8-0d40-4102-ba85-8ab791016234.svg"
                    />
                    <div className={styles.groupTwentyFive}>
                      <img
                        alt=""
                        className={styles.groupTwentyFour}
                        src="https://static.overlay-tech.com/assets/5b2979c2-3f83-4c78-a9ad-747c86108280.svg"
                      />
                      <img
                        alt=""
                        className={styles.vectorSeven}
                        src="https://static.overlay-tech.com/assets/cf37f2f9-3742-4660-a755-bc1c64d4396a.svg"
                      />
                    </div>
                  </div>
                </div>
                <div className={styles.flexWrapperFifty}>
                  <img
                    alt=""
                    className={styles.vectorEight}
                    src="https://static.overlay-tech.com/assets/49a30dbc-68fe-4b1e-a12c-d326873b0ee4.svg"
                  />
                </div>
                <div className={styles.groupThirty}>
                  <img
                    alt=""
                    className={styles.groupTwentySeven}
                    src="https://static.overlay-tech.com/assets/c9c56b40-5f80-40a4-82fe-8332efb66de9.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorThirtyThree}
                    src="https://static.overlay-tech.com/assets/4dce1203-0842-463c-9dcd-f0f2821dbd2d.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorThirtyFour}
                    src="https://static.overlay-tech.com/assets/0d1c0d6c-f8e0-4f36-af34-e2c83c775ab5.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorThirtyFive}
                    src="https://static.overlay-tech.com/assets/b124d981-953f-4a04-9fad-0c87659e0722.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorThirtySix}
                    src="https://static.overlay-tech.com/assets/a8ebb7e3-1c1e-4fa4-ac09-901f281f8374.svg"
                  />
                  <img
                    alt=""
                    className={styles.groupTwentyEight}
                    src="https://static.overlay-tech.com/assets/4dd83eb1-16f3-49a3-9b2d-56dc06ab8ce4.svg"
                  />
                  <img
                    alt=""
                    className={styles.groupTwentyNine}
                    src="https://static.overlay-tech.com/assets/b25bb0dd-fae1-4dd6-b1d0-4f60b94f34ea.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorThirtySeven}
                    src="https://static.overlay-tech.com/assets/f1026939-d426-474e-885f-8fa6824bb3e0.svg"
                  />
                  <img
                    alt=""
                    className={styles.vectorThirtyEight}
                    src="https://static.overlay-tech.com/assets/96fd0d98-173a-4aa4-a748-c08675f3f595.svg"
                  />
                </div>
              </div>
            </div>
            <img
              alt=""
              className={styles.wiFiSignalFour}
              src="https://static.overlay-tech.com/assets/dce5c772-b6c9-4eb0-a9b2-d734a65d37e5.svg"
            />
            <img
              alt=""
              className={styles.batteryFour}
              src="https://static.overlay-tech.com/assets/975a13d8-33a8-4418-8794-7ed209ff6fc9.svg"
            />
          </div>
          <p
            className={
              styles.howDoYouThinkAboutThisAppsPageDTwo
            }
          >
            How do you think about this APP’s page design?
          </p>
          <div className={styles.flexWrapperFiftyThree}>
            <div className={styles.rectangle41Two} />
            <div className={styles.rectangle44Two} />
            <div className={styles.rectangle43Two} />
            <p className={styles.badThree}>Bad</p>
            <div className={styles.rectangle42Two} />
            <p className={styles.excellentThree}>
              Excellent
            </p>
            <p className={styles.goodThree}>Good</p>
          </div>
          <div className={styles.relativeWrapperThirtyTwo}>
            <p className={styles.howIsThisAppsUsibilityTwo}>
              How is this APP’s usibility?
            </p>
            <div className={styles.flexWrapperFiftyFour}>
              <div className={styles.rectangle41Two} />
              <div className={styles.rectangle44Two} />
              <div className={styles.rectangle43Two} />
              <p className={styles.badFour}>Bad</p>
              <div className={styles.rectangle42Two} />
              <p className={styles.excellentFour}>
                Excellent
              </p>
              <p className={styles.goodFour}>Good</p>
            </div>
          </div>
          <div
            className={styles.relativeWrapperThirtyThree}
          >
            <p
              className={
                styles.howWouldYouRecommendThisAppToYourTwo
              }
            >
              How would you recommend this APP to your
              friends? Rate from 1 to 3.
            </p>
            <div className={styles.flexWrapperFiftyFive}>
              <div className={styles.rectangle41Two} />
              <div className={styles.rectangle34} />
              <div className={styles.rectangle33} />
              <p className={styles.num1Two}>1</p>
              <div className={styles.rectangle32} />
              <p className={styles.num3Two}>3</p>
              <p className={styles.num2Two}>2</p>
            </div>
          </div>
          <div className={styles.relativeWrapperThirtyOne}>
            <div className={styles.flexWrapperFiftyTwo}>
              <div className={styles.rectangle9} />
            </div>
            <p className={styles.yourPhoneNumberOrEmailTwo}>
              Your Phone Number or Email
            </p>
          </div>
          <div className={styles.relativeWrapperThirty}>
            <div className={styles.flexWrapperFiftyOne}>
              <div className={styles.rectangle9} />
            </div>
            <p
              className={
                styles.pleaseGiveSomeRecommendationHereTwo
              }
            >
              Please give some recommendation here...
            </p>
            <div className={styles.flexWrapperFiftySix}>
              <div className={styles.rectangle46} />
              <p className={styles.sendTwo}>Send</p>
            </div>
          </div>
        </div>
        <div className={styles.signInPageTwo}>
          <div className={styles.relativeWrapperThree}>
            <div className={styles.ellipse4} />
            <div className={styles.ellipse6} />
            <div className={styles.ellipse3} />
            <div className={styles.flexWrapperFortyEight}>
              <div className={styles.rectangle3Three} />
            </div>
            <p className={styles.forgetPasswordFour}>
              Forget Password
            </p>
            <div className={styles.flexWrapperFortyNine}>
              <div className={styles.rectangle4} />
              <div className={styles.rectangle3Four} />
              <p className={styles.signInFour}>Sign In</p>
            </div>
          </div>
          <div className={styles.relativeWrapperFour}>
            <div className={styles.ellipse5} />
            <div className={styles.flexWrapperTen}>
              <div className={styles.ellipse2Three} />
              <img
                alt=""
                className={styles.sim1SignalThree}
                src="https://static.overlay-tech.com/assets/047cd7fb-6d85-487e-af87-ffba943d77fe.svg"
              />
              <img
                alt=""
                className={styles.wiFiSignalThree}
                src="https://static.overlay-tech.com/assets/e49133bd-222f-4576-98b3-2ef9f4a78434.svg"
              />
              <img
                alt=""
                className={styles.batteryThree}
                src="https://static.overlay-tech.com/assets/0b1b9f4a-b9e7-4e67-8d76-4c160470fd81.svg"
              />
              <div className={styles.ellipse3Two} />
              <div className={styles.ellipse8} />
              <div className={styles.ellipse9} />
              <p className={styles.num915Three}>9:15</p>
              <img
                alt=""
                className={styles.bluetoothThree}
                src="https://static.overlay-tech.com/assets/df9ba634-e07a-4e3f-88c3-fae0ee161e40.svg"
              />
              <img
                alt=""
                className={styles.backTwo}
                src="https://static.overlay-tech.com/assets/c6a418f6-7db1-4a51-b0dc-74d33c3aa8b1.svg"
              />
              <img
                alt=""
                className={styles.toHomePageTwo}
                src="https://static.overlay-tech.com/assets/69977f9a-9478-4e0f-882a-972ca3cefa21.svg"
              />
              <img
                alt=""
                className={
                  styles.undrawTutorialVideoReWepc1Two
                }
                src="https://static.overlay-tech.com/assets/a8d4eb94-9b72-4073-8260-fd816a9c750b.svg"
              />
            </div>
          </div>
          <div className={styles.relativeWrapperSeven}>
            <div className={styles.flexWrapperFortySeven}>
              <div className={styles.rectangle9} />
            </div>
            <p className={styles.userNameTwo}>User Name</p>
            <div className={styles.homeTwo} />
            <div className={styles.homeTwo} />
          </div>
          <p className={styles.passwordTwo}>Password</p>
        </div>
      </div>
      <div className={styles.flexWrapperSeventyThree}>
        <div className={styles.relativeWrapperFortyTwo}>
          <div className={styles.iPhone13ProMaxUserPage}>
            <div className={styles.flexWrapperEightySix}>
              <img
                alt=""
                className={styles.bluetoothTwo}
                src="https://static.overlay-tech.com/assets/14f710d9-e04d-4871-985b-70606831e606.svg"
              />
              <p className={styles.num915Two}>9:15</p>
              <img
                alt=""
                className={styles.sim1SignalTwo}
                src="https://static.overlay-tech.com/assets/e21fde7e-9fe1-4b15-a8ad-4165fd31378f.svg"
              />
              <img
                alt=""
                className={styles.wiFiSignalTwo}
                src="https://static.overlay-tech.com/assets/22d800f4-f164-4c72-b2e0-face9659814b.svg"
              />
              <img
                alt=""
                className={styles.batteryTwo}
                src="https://static.overlay-tech.com/assets/b0d8935d-fea1-4ac2-a70b-f90a755d9b78.svg"
              />
            </div>
            <img
              alt=""
              className={styles.vectorThirtyNine}
              src="https://static.overlay-tech.com/assets/c4587450-56c2-4e79-904e-d177683f0122.svg"
            />
            <img
              alt=""
              className={
                styles.fbImg1590659851920Edit42299739636566
              }
              src="https://static.overlay-tech.com/assets/a79299a1-979d-45ec-9ce9-1db5e506fb6d.png"
            />
            <p className={styles.changeAProfilePhoto}>
              Change a Profile Photo
            </p>
            <div className={styles.flexWrapperTwentyNine}>
              <div className={styles.rectangle31} />
              <p
                className={styles.continueFromWhereYouLeft}
              >
                Continue from where you left:
                <br />
              </p>
              <img
                alt=""
                className={styles.continue1}
                src="https://static.overlay-tech.com/assets/c6ac2f2b-dd65-4906-8623-59215252d20e.png"
              />
            </div>
            <div className={styles.relativeWrapperSixteen}>
              <div
                className={styles.flexWrapperTwentyEight}
              >
                <div className={styles.rectangle27Three} />
              </div>
              <p className={styles.mapSearch}>Map Search</p>
            </div>
            <div className={styles.flexWrapperTwentySeven}>
              <div className={styles.rectangle25Three} />
              <p className={styles.quicklyStartARoute}>
                Quickly Start a Route
              </p>
            </div>
            <div className={styles.relativeWrapperFifteen}>
              <div className={styles.flexWrapperTwentySix}>
                <div className={styles.rectangle27Three} />
              </div>
              <p className={styles.mapSearch}>
                Learning History
              </p>
            </div>
            <div className={styles.relativeWrapperFourteen}>
              <div className={styles.flexWrapperTwentyFour}>
                <div className={styles.rectangle27Three} />
              </div>
              <p className={styles.feedbackThree}>
                Feedback
              </p>
              <div className={styles.flexWrapperTwentyFive}>
                <div className={styles.rectangle25Three} />
                <p className={styles.signOut}>Sign Out</p>
              </div>
            </div>
          </div>
          <div className={styles.alignRight} />
        </div>
        <div className={styles.homeThree} />
        <div className={styles.relativeWrapperFortyOne}>
          <div className={styles.registerPage}>
            <div className={styles.flexWrapperSeventyNine}>
              <img
                alt=""
                className={styles.bluetooth}
                src="https://static.overlay-tech.com/assets/ff75365a-8463-477c-8b0c-0b7c57a16fdb.svg"
              />
              <p className={styles.num915}>9:15</p>
              <img
                alt=""
                className={styles.sim1Signal}
                src="https://static.overlay-tech.com/assets/f07fea89-4971-47d5-ba89-1746d48d6d95.svg"
              />
              <img
                alt=""
                className={styles.wiFiSignal}
                src="https://static.overlay-tech.com/assets/d2c857f1-62cb-4ad8-8f6f-cb77ad9dc798.svg"
              />
              <img
                alt=""
                className={styles.battery}
                src="https://static.overlay-tech.com/assets/73575ac3-5bae-4ffe-806e-ebeff8162feb.svg"
              />
            </div>
            <div className={styles.flexWrapperEightyFive}>
              <img
                alt=""
                className={styles.toHomePage}
                src="https://static.overlay-tech.com/assets/790802f5-db0b-4dc5-9049-d57a03f4307d.svg"
              />
              <img
                alt=""
                className={styles.back}
                src="https://static.overlay-tech.com/assets/09d356b2-c2ef-4597-8bed-99ce3602897b.svg"
              />
            </div>
            <div className={styles.undrawProfilePicRe78k01}>
              <div className={styles.groupThirtyOne}>
                <img
                  alt=""
                  className={styles.vectorForty}
                  src="https://static.overlay-tech.com/assets/5716e651-5bfe-4f27-990d-6c997be58367.svg"
                />
                <img
                  alt=""
                  className={styles.vectorFortyOne}
                  src="https://static.overlay-tech.com/assets/6b70e82c-2076-41ee-a92d-bba991074a7b.svg"
                />
                <img
                  alt=""
                  className={styles.vectorFortyTwo}
                  src="https://static.overlay-tech.com/assets/8b77347f-900c-4605-9a88-7c49d67e204e.svg"
                />
                <div className={styles.flexWrapperOne}>
                  <div
                    className={styles.vectorFortyThree}
                  />
                  <img
                    alt=""
                    className={styles.vectorFortyFour}
                    src="https://static.overlay-tech.com/assets/cb6fba87-114b-4615-9215-dae0b2022bf8.svg"
                  />
                </div>
              </div>
            </div>
            <p className={styles.chooseAProfilePhoto}>
              Choose a Profile Photo
            </p>
            <div className={styles.relativeWrapperTwo}>
              <div className={styles.flexWrapperTwo}>
                <div className={styles.relativeWrapperOne}>
                  <div className={styles.rectangle3Five} />
                  <p className={styles.candice}>Candice</p>
                </div>
                <div className={styles.rectangle5} />
              </div>
              <p className={styles.l}>L</p>
            </div>
            <div className={styles.flexWrapperFour}>
              <div className={styles.rectangle3Five} />
              <p className={styles.female}>Female</p>
              <img
                alt=""
                className={styles.polygon1}
                src="https://static.overlay-tech.com/assets/5e9a8b69-b26d-41c1-94f5-7f0be377776f.svg"
              />
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.female}>User Name</p>
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.birthdayDdMmYyyy}>
                Birthday (dd/mm/yyyy)
              </p>
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.homeAddress}>
                Home Address
              </p>
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.homeAddress}>
                Email Address
              </p>
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.passwordThree}>
                Password
              </p>
            </div>
            <div className={styles.flexWrapperNine}>
              <div className={styles.rectangle6Three} />
              <p className={styles.registerThree}>
                Register
              </p>
            </div>
          </div>
          <div className={styles.homeFour} />
          <div className={styles.homeFour} />
        </div>
        <div className={styles.relativeWrapperFortyFour}>
          <div className={styles.iPhone13ProMaxUserPageTwo}>
            <div className={styles.flexWrapperEightySix}>
              <img
                alt=""
                className={styles.bluetoothTwo}
                src="https://static.overlay-tech.com/assets/e8bec296-c09d-45a6-be99-c2ae862269dc.svg"
              />
              <p className={styles.num915Two}>9:15</p>
              <img
                alt=""
                className={styles.sim1SignalTwo}
                src="https://static.overlay-tech.com/assets/68a51ebd-6df2-4d3b-9a42-ed2d0d227f33.svg"
              />
              <img
                alt=""
                className={styles.wiFiSignalTwo}
                src="https://static.overlay-tech.com/assets/8c9e4645-fd30-4b85-9122-e4dd24472dc2.svg"
              />
              <img
                alt=""
                className={styles.batteryTwo}
                src="https://static.overlay-tech.com/assets/9d67cfa9-e2b6-4f87-a1d9-80e5c72f1690.svg"
              />
            </div>
            <div className={styles.flexWrapperNinety}>
              <img
                alt=""
                className={styles.vectorFortyFive}
                src="https://static.overlay-tech.com/assets/5486b2d3-f80c-4e32-a14d-5e90e703f400.svg"
              />
              <div
                className={styles.relativeWrapperThirtyFour}
              >
                <p
                  className={styles.changeAProfilePhotoTwo}
                >
                  Change a Profile Photo
                </p>
                <img
                  alt=""
                  className={
                    styles.fbImg1590659851920Edit42299739636566Two
                  }
                  src="https://static.overlay-tech.com/assets/bd040eb7-dcbc-4062-bd84-b13d1e66648e.png"
                />
              </div>
            </div>
            <div className={styles.flexWrapperSixtyTwo}>
              <div className={styles.rectangle31} />
              <p
                className={
                  styles.continueFromWhereYouLeftTwo
                }
              >
                Continue from where you left:
                <br />
              </p>
              <img
                alt=""
                className={styles.continue1Two}
                src="https://static.overlay-tech.com/assets/0de9683d-48fc-4025-bc33-eda9be05049e.png"
              />
            </div>
            <div
              className={styles.relativeWrapperThirtySeven}
            >
              <div className={styles.flexWrapperSixtyOne}>
                <div className={styles.rectangle27Three} />
              </div>
              <p className={styles.mapSearchTwo}>
                Map Search
              </p>
            </div>
            <div className={styles.flexWrapperSixty}>
              <div className={styles.rectangle25Four} />
              <p className={styles.quicklyStartARouteTwo}>
                Quickly Start a Route
              </p>
            </div>
            <div
              className={styles.relativeWrapperThirtySix}
            >
              <div className={styles.flexWrapperFiftyNine}>
                <div className={styles.rectangle27Three} />
              </div>
              <p className={styles.mapSearchTwo}>
                Learning History
              </p>
            </div>
            <div
              className={styles.relativeWrapperThirtyFive}
            >
              <div className={styles.flexWrapperFiftySeven}>
                <div className={styles.rectangle27Three} />
              </div>
              <p className={styles.mapSearchTwo}>
                Feedback
              </p>
            </div>
            <div className={styles.flexWrapperFiftyEight}>
              <div className={styles.rectangle29} />
              <p className={styles.mapSearchTwo}>
                Sign Out
              </p>
            </div>
          </div>
          <div className={styles.alignRight} />
        </div>
        <div className={styles.homeFive} />
        <div className={styles.relativeWrapperFortyFour}>
          <div className={styles.registerPageTwo}>
            <div className={styles.flexWrapperSeventyNine}>
              <img
                alt=""
                className={styles.bluetooth}
                src="https://static.overlay-tech.com/assets/1ad24ac0-dfd9-4581-9be3-ce97dac5699d.svg"
              />
              <p className={styles.num915}>9:15</p>
              <img
                alt=""
                className={styles.sim1Signal}
                src="https://static.overlay-tech.com/assets/8b7a359b-3ac8-4618-a22f-6fdb62da5e93.svg"
              />
              <img
                alt=""
                className={styles.wiFiSignal}
                src="https://static.overlay-tech.com/assets/70121379-18ab-45f9-9857-715051df19a0.svg"
              />
              <img
                alt=""
                className={styles.battery}
                src="https://static.overlay-tech.com/assets/6e392504-ea2e-4e5a-9ace-8b5a04d9fd4a.svg"
              />
            </div>
            <div className={styles.flexWrapperEightyFive}>
              <img
                alt=""
                className={styles.toHomePage}
                src="https://static.overlay-tech.com/assets/296ecd5b-1d50-4540-adbe-8f206ed4cd0f.svg"
              />
              <img
                alt=""
                className={styles.back}
                src="https://static.overlay-tech.com/assets/e313df49-9f5c-4203-88b2-50a3a5340f79.svg"
              />
            </div>
            <div
              className={styles.undrawProfilePicRe78k01Two}
            >
              <div className={styles.groupThirtyOne}>
                <img
                  alt=""
                  className={styles.vectorForty}
                  src="https://static.overlay-tech.com/assets/6877d6f0-6581-4441-aa4f-c878604e26aa.svg"
                />
                <img
                  alt=""
                  className={styles.vectorFortyOne}
                  src="https://static.overlay-tech.com/assets/6a0fe09a-93ac-4866-afbb-a50e73fcd056.svg"
                />
                <img
                  alt=""
                  className={styles.vectorFortyTwo}
                  src="https://static.overlay-tech.com/assets/aed1d09a-5c90-49ec-b777-f9f8b7547cc0.svg"
                />
                <div
                  className={styles.flexWrapperThirtySeven}
                >
                  <div
                    className={styles.vectorFortyThree}
                  />
                  <img
                    alt=""
                    className={styles.vectorFortyFour}
                    src="https://static.overlay-tech.com/assets/7e378a81-87b8-4a72-bda3-19d42483b404.svg"
                  />
                </div>
              </div>
            </div>
            <p className={styles.chooseAProfilePhotoTwo}>
              Choose a Profile Photo
            </p>
            <div className={styles.relativeWrapperTwo}>
              <div className={styles.flexWrapperTwo}>
                <div className={styles.relativeWrapperOne}>
                  <div className={styles.rectangle3Five} />
                  <p className={styles.candiceTwo}>
                    Candice
                  </p>
                </div>
                <div className={styles.rectangle5} />
              </div>
              <p className={styles.lTwo}>L</p>
            </div>
            <div className={styles.flexWrapperFour}>
              <div className={styles.rectangle3Five} />
              <p className={styles.femaleTwo}>Female</p>
              <img
                alt=""
                className={styles.polygon1}
                src="https://static.overlay-tech.com/assets/23c384cb-79ad-4994-978f-b128460fa1a2.svg"
              />
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.userNameThree}>
                User Name
              </p>
            </div>
            <div className={styles.relativeWrapperTwo}>
              <div className={styles.flexWrapperEleven}>
                <div className={styles.rectangle9} />
              </div>
              <p className={styles.birthdayDdMmYyyyTwo}>
                Birthday (dd/mm/yyyy)
              </p>
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.homeAddressTwo}>
                Home Address
              </p>
            </div>
            <div className={styles.flexWrapperThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.emailAddress}>
                Email Address
              </p>
            </div>
            <div className={styles.flexWrapperFortyThree}>
              <div className={styles.rectangle6Three} />
              <p className={styles.homeAddressTwo}>
                Password
              </p>
            </div>
            <div className={styles.flexWrapperFortyFive}>
              <div className={styles.rectangle6Three} />
              <p className={styles.registerFour}>
                Register
              </p>
            </div>
          </div>
          <div className={styles.homeFour} />
          <div className={styles.homeFour} />
        </div>
      </div>
      <div className={styles.flexWrapperSeventyFive}>
        <div className={styles.drivingPage}>
          <img
            alt=""
            className={styles.s4zu1}
            src="https://static.overlay-tech.com/assets/6f7090e1-3525-4f9a-8e7f-5b59f82ac348.png"
          />
          <img
            alt=""
            className={styles.toHomePageFour}
            src="https://static.overlay-tech.com/assets/04778747-d81a-4ccf-81a2-4f3da27321ba.svg"
          />
          <img
            alt=""
            className={styles.backFour}
            src="https://static.overlay-tech.com/assets/f2d1e3fb-479e-4cad-b388-6aca760b2523.svg"
          />
          <p className={styles.or}>OR</p>
          <FbImg1590659851920Edit42299739636566
            className={
              styles.fbImg1590659851920Edit42299739636566Three
            }
          />
        </div>
        <div className={styles.flexWrapperSeventy}>
          <MapSearch className={styles.mapSearchThree} />
          <FbImg1590659851920Edit42299739636566
            className={
              styles.fbImg1590659851920Edit42299739636566Four
            }
          />
          <div className={styles.kickstarterK} />
          <div className={styles.kickstarterK} />
        </div>
        <div className={styles.drivingPageTwo}>
          <img
            alt=""
            className={styles.s4zu1}
            src="https://static.overlay-tech.com/assets/7008d513-2af5-4616-9b34-a3f78f538244.png"
          />
          <img
            alt=""
            className={styles.toHomePageFive}
            src="https://static.overlay-tech.com/assets/a4ff2acb-1ede-4673-a355-6e89cd9a9b32.svg"
          />
          <img
            alt=""
            className={styles.backFive}
            src="https://static.overlay-tech.com/assets/50a3b70e-a834-461f-8055-4adfed071f25.svg"
          />
          <p className={styles.orTwo}>OR</p>
          <FbImg1590659851920Edit42299739636566
            className={
              styles.fbImg1590659851920Edit42299739636566Five
            }
          />
        </div>
        <div className={styles.flexWrapperSeventyOne}>
          <MapSearch className={styles.mapSearchThree} />
          <FbImg1590659851920Edit42299739636566
            className={
              styles.fbImg1590659851920Edit42299739636566Four
            }
          />
          <div className={styles.kickstarterK} />
          <div className={styles.kickstarterK} />
        </div>
      </div>
    </div>
  );
};

export default Num826Total;
