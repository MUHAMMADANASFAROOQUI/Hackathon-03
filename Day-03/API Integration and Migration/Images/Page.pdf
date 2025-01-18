import Image from "next/image";
import Header from "./components/navbar";
import Link from "next/link";
import Card1 from "../app/public/card1.jpeg";
import Card2 from "../app/public/card2.jpeg";
import image7 from "../app/public/image7.png";
import image8 from "../app/public/image8.png";
import mark from "../app/public/mark.png";
import Switch from "../app/public/Switch.png";
import spesfication from "../app/public/spesfication.png";
import Like2 from "../app/public/Like2.png";
import Car from "../app/public/Car.png";
import spesfication2 from "../app/public/spesfication2.png";
import spesfication3 from "../app/public/spesfication3.png";
import Footer from "./components/footer";

import { sanityFetch } from "@/sanity/lib/client";
import { allcars } from "@/sanity/lib/queries";






type Car = {
  _id: string;
  name: string;
  type: string;
  fuel_capacity: string;
  transmission: string;
  seating_capacity: string;
  price_per_day: number;
  tags: string;
  image: string;
};

export default async function Home() {
  const cars: Car[] = await sanityFetch({ query: allcars });
  return (
    <div>
      <div>
        <Header />
      </div>
      <div className="hero-section">
        <div className="" style={{ background: "#F6F7F9" }}>
          <div className="flex">
            <div className="md:ml-[64px] ml-[25px] mt-[32px] md:w-[640px] w-[327px] md:h-[360px] h-[232px] rounded-[10px] ">
              <Image
                src={Card2}
                alt="hero1"
                width={640}
                height={360}
                className="bg-cover bg-center w-full h-full"
              />
              <div className=" md:mt-[80px] mt-[80px] md:w-[284px] w-[240px] h-[70px]  md:h-[224px] gap-y-[10px] absolute md:inset-24 inset-12 ">
                <h1 className="font-semibold md:text-[32px] text-[16px] tracking-percent leading-[150%] w-[272px] h-[96px] text-white">
                  The Best Platform for Car Rental
                </h1>
                <p className="text-[16px] w-[284px] h-[46px] mt-3  text-white">
                  Ease of doing a car rental safely and reliably. Of course at a
                  low price.
                </p>
                <div className="text-[16px] w-[120px] h-[44px] bg-primary1 mt-3 pl-[20px] pt-[10px] text-white">
                  <Link href={"/detail-car-rent"}>Rental Car</Link>
                </div>
              </div>
              <Image
                src={image7}
                alt="car1"
                className="absolute md:inset-44 inset-20 md:mt-52 mt-[266px] md:w-[406px] w-[196px] md:h-[116px] h-[56px]"
              ></Image>
            </div>
            <div className="md:ml-[32px] md:mr-[64px] md:mt-[32px] md:w-[640px] md:h-[360px]  md:rounded-[10px] md:flex hidden ">
              <Image
                src={Card1}
                alt="hero1"
                width={640}
                height={360}
                className="bg-cover bg-center w-full h-full"
              />
              <div>
                <div className="mt-5  w-[284px] h-[224px] gap-y-[10px] absolute inset-x-[680px]">
                  <h1 className="font-semibold text-[32px] tracking-percent leading-[150%] text-white w-[272px] h-[96px]">
                    Easy way to rent a car at a low price
                  </h1>
                  <p className="text-[16px] w-[284px] h-[46px] mt-3 text-white">
                    Providing cheap car rental services and safe and comfortable
                    facilities.
                  </p>
                  <div
                    className="text-[16px] w-[120px] h-[44px] pl-[20px] pt-[10px] mt-3 text-white"
                    style={{ backgroundColor: "#54A6FF" }}
                  >
                    <Link href="/detail-car-rent">Rental Car</Link>
                  </div>
                </div>
                <Image
                  src={image8}
                  alt="car1"
                  className="absolute inset-x-[790px] mt-56 w-[340px] h-[108px]"
                ></Image>
              </div>
            </div>
          </div>
          <div className="md:flex">
            <div className="md:w-[500px] w-[327px]  md:h-[132px] h-[120px] md:ml-[64px] ml-[24px] mt-[32px] bg-white ">
              <div className="flex md:ml-[40px] ml-[20px]">
                <Image
                  src={mark}
                  alt="mark1"
                  className=" w-[16px] h-[16px] mt-[24px] mr-[8px]"
                ></Image>
                <h1 className="text-[16px] leading-[150%] tracking-percent1 font-semibold mt-[19px]">
                  Pick - Up
                </h1>
              </div>

              <div className="w-[486px] h-[48px] md:ml-[40px] ml-[10px] md:mt-[20px] mt-[16px] flex">
                <div className="md:w-[140px] w-[110px] h-[48px] border-r-[1px]">
                  <h1 className="font-bold text-[16px] leading-[150%] tracking-percent1">
                    Locations
                  </h1>
                  <select
                    name="Select your city"
                    id="0"
                    className="text-[12px] md:w-[126px] w-[100px] h-[20px] mr-3"
                  >
                    <option
                      value="Select your city"
                      className="hidden md:w-[126px]"
                    >
                      Select your city
                    </option>
                    <option value="Semarang">Semarang</option>
                    <option value="Lahore">Lahore</option>
                    <option value="Islamabad">Islamabad</option>
                    <option value="Peshawar">Peshawar</option>
                  </select>
                </div>
                <div className="w-[486px] h-[48px] ml-[10px]  ">
                  <div className="md:w-[140px] w-[110px] h-[48px] border-r-[1px]">
                    <h1 className="font-bold text-[16px] leading-[150%] tracking-percent1">
                      Date
                    </h1>
                    <select
                      name="Select your city"
                      id="0"
                      className="text-[12px] md:w-[126px] w-[100px] h-[20px]"
                    >
                      <option
                        value="Select your city"
                        className="hidden md:w-[126px]"
                      >
                        Select your date
                      </option>
                      <option value="21 July 2022">21 July 2022 </option>
                      <option value="9-12-2024">09-12-2024</option>
                      <option value="10-12-2024">10-12-2024</option>
                      <option value="12-12-2024">11-12-2024</option>
                    </select>
                  </div>
                </div>
                <div className="w-[486px] h-[48px]  mr-[120px] md:mr-[0px] ">
                  <div className="md:w-[140px] w-[110px] h-[48px] ">
                    <h1 className="font-bold text-[16px] leading-[150%] tracking-percent1">
                      Time
                    </h1>
                    <select
                      name="Select your city"
                      id="0"
                      className="text-[12px] md:w-[126px] w-[70px] h-[20px] mr-[10px]"
                    >
                      <option
                        value="Select your city"
                        className="hidden md:w-[126px]"
                      >
                        Select time
                      </option>
                      <option value="07.00">07.00</option>
                      <option value="11:00 am">11:00 am</option>
                      <option value="12:00 pm">12:00 pm</option>
                      <option value="01:00 pm">01:00 pm</option>
                    </select>
                  </div>
                </div>
              </div>
            </div>
            <div>
              <Image
                src={Switch}
                alt="switch"
                className="w-30 h-30 md:ml-[0px] ml-[100px] md:mt-[60px]"
              ></Image>
            </div>
            <div className="md:w-[500px] w-[327px] h-[132px] md:ml-[10px] ml-[24px] mr-[64px] md:mt-[32px]  bg-white ">
              <div className="flex md:ml-[40px] ml-[20px]">
                <Image
                  src={mark}
                  alt="mark1"
                  className=" w-[16px] h-[16px] mt-[24px] mr-[8px]"
                ></Image>
                <h1 className="text-[16px] leading-[150%] tracking-percent1 font-semibold mt-[19px]">
                  Drop - Off
                </h1>
              </div>

              <div className="w-[486px] h-[48px] md:ml-[40px] ml-[10px] mt-[20px] flex">
                <div className="md:w-[140px] w-[110px] h-[48px] border-r-[1px]">
                  <h1 className="font-bold text-[16px] leading-[150%] tracking-percent1">
                    Locations
                  </h1>
                  <select
                    name="Select your city"
                    id="0"
                    className="text-[12px] md:w-[126px] w-[100px] h-[20px] mr-3"
                  >
                    <option value="Select your city">Select your city</option>
                    <option value="Karachi">Karachi</option>
                    <option value="Lahore">Lahore</option>
                    <option value="Islamabad">Islamabad</option>
                    <option value="Peshawar">Peshawar</option>
                  </select>
                </div>
                <div className="w-[486px] h-[48px] ml-[14px]  ">
                  <div className="md:w-[140px] w-[110px] h-[48px] border-r-[1px]">
                    <h1 className="font-bold text-[16px] leading-[150%] tracking-percent1">
                      Date
                    </h1>
                    <select
                      name="Select your city"
                      id="0"
                      className="text-[12px] md:w-[126px] w-[100px] h-[20px]"
                    >
                      <option value="Select your city">Select your date</option>
                      <option value="8-12-2024">08-12-2024</option>
                      <option value="9-12-2024">09-12-2024</option>
                      <option value="10-12-2024">10-12-2024</option>
                      <option value="12-12-2024">11-12-2024</option>
                    </select>
                  </div>
                </div>
                <div className="w-[486px] h-[48px]  mr-[120px]  ">
                  <div className="md:w-[140px] w-[110px] h-[48px] ">
                    <h1 className="font-bold text-[16px] leading-[150%] tracking-percent1">
                      Time
                    </h1>
                    <select
                      name="Select your city"
                      id="0"
                      className="text-[12px] md:w-[126px] w-[70px] h-[20px]"
                    >
                      <option value="Select your city">Select time</option>
                      <option value="10:00 am">10:00 am</option>
                      <option value="11:00 am">11:00 am</option>
                      <option value="12:00 pm">12:00 pm</option>
                      <option value="01:00 pm">01:00 pm</option>
                    </select>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div className="cards-section">
            <div
              className="pt-[24px] md:pl-[64px] pr-[64px]"
              style={{ backgroundColor: "#F6F7F9" }}
            >
              <div className="flex justify-between items-center">
                <div>
                  <h1 className="text-[16px] font-semibold ml-[20px] mt-[18px] text-text1">
                    Popular Car
                  </h1>
                </div>
                <div className="md:w-[104px] w-[210px] h-[44px] mt-[18px] pt-[4px] ">
                  <Link
                    href={"/category-car-rent"}
                    className="  pl-[100px] md:pl-[0px] font-semibold text-[16px] text-primary1"
                  >
                    View All
                  </Link>
                </div>
              </div>

              <div className="flex gap-8 md:mt-[64px] mt-[24px] justify-center sm:justify-start sm:gap-6 md:gap-6 flex-wrap">
                {/* <div className="w-[290px] h-[388px] bg-white rounded-[10px]">
        <div className="w-[128px] h-[48px] p-[20px] gap-x-[4px] flex"> */}
                <div className="grid grid-cols-4 gap-5  ">
                  {cars.map((car) => (
                    <div
                      className="w-[270px] h-[388px] bg-white rounded-[10px] "
                      key={car._id}
                    >
                      <div className="flex m-4 pt-[8px]">
                        <div className="w-[250px]">
                          <h2 className="text-xl font-bold ">{car.name}</h2>
                          <p className="opacity-50">{car.type}</p>
                        </div>
                        <div className="ml-[0px]">
                          <Image
                            src={Like2}
                            alt="like"
                            className="w-[25px] h-[25px]"
                          />
                        </div>
                      </div>
                      <div className="h-[90px]">
                        <Image
                          src={car.image}
                          alt={car.name}
                          className="w-60 mt-[100px] mx-[20px] "
                          height={200}
                          width={300}
                        />
                      </div>
                      <div className="grid grid-cols-3 mt-5 ml-3 mr-3 ">
                        <p className=" flex">
                          <Image
                            src={spesfication}
                            alt="fuel"
                            className="w-[20px] h-[20px]"
                          />
                          {car.fuel_capacity}
                        </p>
                        <p className="flex">
                          <Image
                            src={spesfication2}
                            alt="fuel"
                            className="w-[20px] h-[20px]"
                          />
                          {car.transmission}
                        </p>
                        <p className="flex">
                          <Image
                            src={spesfication3}
                            alt="fuel"
                            className="w-[20px] h-[20px]"
                          />
                          {car.seating_capacity}
                        </p>
                      </div>

                      <div>
                        <div className="flex ml-4 mt-3 gap-4">
                          <div className="flex w-[100px] ">
                            <h2 className="text-2xl font-bold">
                              ${car.price_per_day}/
                            </h2>
                            <h2 className="opacity-50 mt-2 ml-1">day</h2>
                          </div>
                          <div className="w-[116px] h-[44px]   bg-primary1 text-[16px] font-semibold mr-[16px] tracking-percent1 text-white text-center rounded-[4px] pt-[8px]">
                            <Link href={`/${car._id}`}>Rent Now</Link>
                          </div>
                        </div>
                      </div>
                    </div>
                  ))}
                  <br />
                  <br />
                  <br />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <Footer />
    </div>
  );
}
