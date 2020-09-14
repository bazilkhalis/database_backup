-- phpMyAdmin SQL Dump
-- version 5.0.2
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Sep 13, 2020 at 11:28 AM
-- Server version: 10.4.13-MariaDB
-- PHP Version: 7.4.8

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `ocs`
--

-- --------------------------------------------------------

--
-- Table structure for table `crud`
--

CREATE TABLE `crud` (
  `id` int(11) NOT NULL,
  `fullname` varchar(255) NOT NULL,
  `ic_no` varchar(9) NOT NULL,
  `driving_license_no` varchar(30) NOT NULL,
  `address` varchar(100) NOT NULL,
  `photo` varchar(255) NOT NULL,
  `date_of_birth` date NOT NULL,
  `date_issued` date NOT NULL,
  `date_expired` date NOT NULL,
  `gender` varchar(10) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `crud`
--

INSERT INTO `crud` (`id`, `fullname`, `ic_no`, `driving_license_no`, `address`, `photo`, `date_of_birth`, `date_issued`, `date_expired`, `gender`) VALUES
(1, 'Muhammad Bazil Khalis Bin Sallehuddin', '01-123277', '12345678909', 'No 16, Spg 59 Tanjung Bunut Kanan', 'uploads/WhatsApp Image 2020-08-25 at 00.37.24.jpeg', '2020-09-05', '2020-09-11', '2020-09-30', 'male'),
(2, 'izzad salleh', '12345678', '12345678456789', 'Katok Area', 'uploads/WhatsApp Image 2020-08-25 at 01.02.52.jpeg', '2020-09-05', '2020-10-02', '2023-11-16', 'male'),
(3, 'Bazil', '12345678', '1324568', 'tutong', 'uploads/', '2020-09-09', '2020-09-02', '2022-09-06', 'male'),
(4, 'Harry potter', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'male'),
(5, 'Luna', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'female'),
(6, 'hermione', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'female'),
(7, 'Arif', '12345678', '1234579078', 'manggis', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'male'),
(8, 'aiman', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'male'),
(9, 'ahmad', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'male'),
(10, 'ryan', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'male'),
(11, 'azli', '12345678', '1234579078', 'London', 'uploads/', '2020-09-06', '2020-09-06', '2022-09-06', 'female'),
(12, 'King', '01-223444', '1234579078', 'tutong', 'uploads/', '2020-09-09', '2020-09-10', '2020-09-10', 'male'),
(13, 'zelda', '01-223444', '1234579078', 'London', 'uploads/', '2020-09-03', '2020-09-10', '2020-09-17', 'male'),
(14, 'Bazil', '01-223444', '1234579078', 'London', 'uploads/', '2020-09-10', '2020-09-10', '2020-09-10', 'male');

-- --------------------------------------------------------

--
-- Table structure for table `immigration`
--

CREATE TABLE `immigration` (
  `id` int(255) NOT NULL,
  `user` varchar(255) NOT NULL,
  `pass` varchar(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `immigration`
--

INSERT INTO `immigration` (`id`, `user`, `pass`) VALUES
(1, 'bazil', '123qweasdzx'),
(2, 'shafiq', '123qweasdzx');

--
-- Indexes for dumped tables
--

--
-- Indexes for table `crud`
--
ALTER TABLE `crud`
  ADD PRIMARY KEY (`id`);

--
-- Indexes for table `immigration`
--
ALTER TABLE `immigration`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `crud`
--
ALTER TABLE `crud`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=15;

--
-- AUTO_INCREMENT for table `immigration`
--
ALTER TABLE `immigration`
  MODIFY `id` int(255) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=3;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
